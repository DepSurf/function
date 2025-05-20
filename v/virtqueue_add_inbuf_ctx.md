# Function: <code>virtqueue_add_inbuf_ctx</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815500a0)
Location: drivers/virtio/virtio_ring.c:531
Inline: False
```
**Symbols:**

```
ffffffff815500a0-ffffffff8155041c: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b38a0)
Location: drivers/virtio/virtio_ring.c:530
Inline: False
```
**Symbols:**

```
ffffffff815b38a0-ffffffff815b3c04: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ec000)
Location: drivers/virtio/virtio_ring.c:529
Inline: False
```
**Symbols:**

```
ffffffff815ec000-ffffffff815ec330: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81606ed0)
Location: drivers/virtio/virtio_ring.c:1799
Inline: False
```
**Symbols:**

```
ffffffff81606ed0-ffffffff81606efb: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8163a160)
Location: drivers/virtio/virtio_ring.c:1804
Inline: False
```
**Symbols:**

```
ffffffff8163a160-ffffffff8163a831: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165c3c0)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffffffff8165c3c0-ffffffff8165ccfb: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170bdf0)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffffffff8170bdf0-ffffffff8170be3f: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81728c60)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffffffff81728c60-ffffffff81728caf: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170c380)
Location: drivers/virtio/virtio_ring.c:1805
Inline: False
```
**Symbols:**

```
ffffffff8170c380-ffffffff8170c3cf: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1903
Inline: False
```
**Symbols:**

```
ffffffff81cf4d37-ffffffff81cf4d69: virtqueue_add_inbuf_ctx.cold (STB_LOCAL)
ffffffff81788750-ffffffff817887c5: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1907
Inline: False
```
**Symbols:**

```
ffffffff81ebceab-ffffffff81ebcede: virtqueue_add_inbuf_ctx.cold (STB_LOCAL)
ffffffff818bfdb0-ffffffff818bfe4c: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2193
Inline: False
```
**Symbols:**

```
ffffffff82094431-ffffffff82094464: virtqueue_add_inbuf_ctx.cold (STB_LOCAL)
ffffffff81a0fc70-ffffffff81a0fd0c: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2230
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:try_fill_recv
```
**Symbols:**

```
ffffffff8211513b-ffffffff8211516e: virtqueue_add_inbuf_ctx.cold (STB_LOCAL)
ffffffff81a58bb0-ffffffff81a58c4c: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2307
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:try_fill_recv
  - drivers/net/virtio_net.c:try_fill_recv
```
**Symbols:**

```
ffffffff821f2da8-ffffffff821f2ddb: virtqueue_add_inbuf_ctx.cold (STB_LOCAL)
ffffffff81aaa040-ffffffff81aaa0dc: virtqueue_add_inbuf_ctx (STB_GLOBAL)
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
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010825328)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffff800010825328-ffff800010825a94: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0941e10)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
c0941e10-c09428d4: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cf970)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
c0000000008cf970-c0000000008d06c8: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051a380)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffffffe00051a380-ffffffe00051abcc: virtqueue_add_inbuf_ctx (STB_GLOBAL)
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
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81622260)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffffffff81622260-ffffffff81622b9b: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816168b0)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffffffff816168b0-ffffffff816171eb: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81650200)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffffffff81650200-ffffffff81650b3b: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int virtqueue_add_inbuf_ctx(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, void *ctx, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8166a890)
Location: drivers/virtio/virtio_ring.c:1803
Inline: False
```
**Symbols:**

```
ffffffff8166a890-ffffffff8166b1cb: virtqueue_add_inbuf_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
