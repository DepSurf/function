# Function: <code>virtqueue_add_packed</code>

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
In drivers/virtio/virtio_ring.c (ffffffff8160631f)
Location: drivers/virtio/virtio_ring.c:1086
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
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8163a192)
Location: drivers/virtio/virtio_ring.c:1091
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
ffffffff81638940-ffffffff81638d1e: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165c3f1)
Location: drivers/virtio/virtio_ring.c:1091
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
ffffffff8165a400-ffffffff8165aa7a: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b860)
Location: drivers/virtio/virtio_ring.c:1091
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff8170b860-ffffffff8170bc75: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817286d0)
Location: drivers/virtio/virtio_ring.c:1091
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff817286d0-ffffffff81728ae5: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170be20)
Location: drivers/virtio/virtio_ring.c:1091
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff8170be20-ffffffff8170c207: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1166
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff817880e0-ffffffff81788564: virtqueue_add_packed (STB_LOCAL)
ffffffff81cf4c0a-ffffffff81cf4ccf: virtqueue_add_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1159
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff818bf6d0-ffffffff818bfb80: virtqueue_add_packed (STB_LOCAL)
ffffffff81ebcd20-ffffffff81ebce40: virtqueue_add_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1344
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81a0f520-ffffffff81a0f9f9: virtqueue_add_packed (STB_LOCAL)
ffffffff820942a6-ffffffff820943c6: virtqueue_add_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1364
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81a585e0-ffffffff81a58a94: virtqueue_add_packed (STB_LOCAL)
ffffffff82115006-ffffffff82115126: virtqueue_add_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1401
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
**Symbols:**

```
ffffffff81aa9990-ffffffff81aa9e78: virtqueue_add_packed (STB_LOCAL)
ffffffff821f2c39-ffffffff821f2d68: virtqueue_add_packed.cold (STB_LOCAL)
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
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010825370)
Location: drivers/virtio/virtio_ring.c:1091
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
ffff800010823a68-ffff800010823ecc: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0941e4c)
Location: drivers/virtio/virtio_ring.c:1091
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
c0940048-c0940820: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cf9d8)
Location: drivers/virtio/virtio_ring.c:1091
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
c0000000008ccd10-c0000000008cd654: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051a3c2)
Location: drivers/virtio/virtio_ring.c:1091
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
ffffffe00051902c-ffffffe000519662: virtqueue_add_packed (STB_LOCAL)
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
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81622291)
Location: drivers/virtio/virtio_ring.c:1091
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
ffffffff816202a0-ffffffff8162091a: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816168e1)
Location: drivers/virtio/virtio_ring.c:1091
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
ffffffff816148f0-ffffffff81614f6a: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81650231)
Location: drivers/virtio/virtio_ring.c:1091
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
ffffffff8164e240-ffffffff8164e8ba: virtqueue_add_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int virtqueue_add_packed(struct virtqueue *_vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8166a8c1)
Location: drivers/virtio/virtio_ring.c:1091
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
ffffffff816688d0-ffffffff81668f4a: virtqueue_add_packed (STB_LOCAL)
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
