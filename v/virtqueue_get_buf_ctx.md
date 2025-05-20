# Function: <code>virtqueue_get_buf_ctx</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f7c0)
Location: drivers/virtio/virtio_ring.c:700
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8154f7c0-ffffffff8154f8ea: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2e80)
Location: drivers/virtio/virtio_ring.c:699
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff815b2e80-ffffffff815b2faa: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eb3b0)
Location: drivers/virtio/virtio_ring.c:698
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff815eb3b0-ffffffff815eb4bc: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816058a0)
Location: drivers/virtio/virtio_ring.c:1889
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff816058a0-ffffffff81605b19: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1895
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8163acab-ffffffff8163ad3f: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff8163aaa0-ffffffff8163ac7d: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8165d16b-ffffffff8165d1ff: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff8165cf60-ffffffff8165d13d: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170ab55)
Location: drivers/virtio/virtio_ring.c:1894
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8170ab30-ffffffff8170ab4d: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817276c5)
Location: drivers/virtio/virtio_ring.c:1894
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff817275e0-ffffffff817275fd: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b305)
Location: drivers/virtio/virtio_ring.c:1896
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8170b020-ffffffff8170b03d: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817874be)
Location: drivers/virtio/virtio_ring.c:1994
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81cf49d4-ffffffff81cf49f0: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff81787350-ffffffff817873a0: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818be650)
Location: drivers/virtio/virtio_ring.c:1998
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81ebc975-ffffffff81ebc992: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff818bdf70-ffffffff818bdfd7: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0db30)
Location: drivers/virtio/virtio_ring.c:2284
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff82093c75-ffffffff82093c92: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff81a0cac0-ffffffff81a0cb27: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a56a80)
Location: drivers/virtio/virtio_ring.c:2321
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
Direct callers:
  - drivers/net/virtio_net.c:receive_mergeable
```
**Symbols:**

```
ffffffff82114c29-ffffffff82114c46: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff81a56290-ffffffff81a562f7: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa7ba0)
Location: drivers/virtio/virtio_ring.c:2415
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
Direct callers:
  - drivers/net/virtio_net.c:virtnet_rq_get_buf
```
**Symbols:**

```
ffffffff821f2855-ffffffff821f2872: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff81aa73b0-ffffffff81aa7417: virtqueue_get_buf_ctx (STB_GLOBAL)
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
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010823128)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffff800010823128-ffff8000108233ec: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0940cb8)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
c0940cb8-c0940f60: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008d0b00)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
c0000000008d0b00-c0000000008d0e90: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000519a0c)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffe000519a0c-ffffffe000519c56: virtqueue_get_buf_ctx (STB_GLOBAL)
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
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8162300b-ffffffff8162309f: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff81622e00-ffffffff81622fdd: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8161765b-ffffffff816176ef: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff81617450-ffffffff8161762d: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81650fab-ffffffff8165103f: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff81650da0-ffffffff81650f7d: virtqueue_get_buf_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1894
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8166b63b-ffffffff8166b6cf: virtqueue_get_buf_ctx.cold (STB_LOCAL)
ffffffff8166b430-ffffffff8166b60d: virtqueue_get_buf_ctx (STB_GLOBAL)
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
