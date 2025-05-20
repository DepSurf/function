# Function: <code>detach_buf_packed</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81605620)
Location: drivers/virtio/virtio_ring.c:1276
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff81605620-ffffffff816057d9: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8163a840)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff8163a840-ffffffff8163a9ec: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165cd00)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff8165cd00-ffffffff8165ceac: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a780)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed
```
**Symbols:**

```
ffffffff8170a780-ffffffff8170a941: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81726cc0)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed
```
**Symbols:**

```
ffffffff81726cc0-ffffffff81726e44: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a940)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed
```
**Symbols:**

```
ffffffff8170a940-ffffffff8170aab6: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1367
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed
```
**Symbols:**

```
ffffffff81786f30-ffffffff817870d5: detach_buf_packed (STB_LOCAL)
ffffffff81cf4875-ffffffff81cf48cf: detach_buf_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1359
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed
```
**Symbols:**

```
ffffffff818bd450-ffffffff818bd5d9: detach_buf_packed (STB_LOCAL)
ffffffff81ebc63c-ffffffff81ebc67b: detach_buf_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1544
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed
```
**Symbols:**

```
ffffffff81a0c2d0-ffffffff81a0c45c: detach_buf_packed (STB_LOCAL)
ffffffff82093b53-ffffffff82093b92: detach_buf_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1564
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed
```
**Symbols:**

```
ffffffff81a551e0-ffffffff81a5536c: detach_buf_packed (STB_LOCAL)
ffffffff82114887-ffffffff821148c6: detach_buf_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1602
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_packed
```
**Symbols:**

```
ffffffff81aa6300-ffffffff81aa648c: detach_buf_packed (STB_LOCAL)
ffffffff821f24a4-ffffffff821f24e3: detach_buf_packed.cold (STB_LOCAL)
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
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010822e80)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffff800010822e80-ffff80001082303c: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0940a1c)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
c0940a1c-c0940bdc: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008d06d0)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
c0000000008d06d0-c0000000008d0964: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000519802)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffe000519802-ffffffe000519964: detach_buf_packed (STB_LOCAL)
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
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81622ba0)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff81622ba0-ffffffff81622d4c: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816171f0)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff816171f0-ffffffff8161739c: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81650b40)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff81650b40-ffffffff81650cec: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void detach_buf_packed(struct vring_virtqueue *vq, unsigned int id, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8166b1d0)
Location: drivers/virtio/virtio_ring.c:1281
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff8166b1d0-ffffffff8166b37c: detach_buf_packed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
