# Function: <code>detach_buf_split</code>

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
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816054e0)
Location: drivers/virtio/virtio_ring.c:618
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff816054e0-ffffffff81605617: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81639310)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff81639310-ffffffff8163943e: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165b090)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff8165b090-ffffffff8165b1be: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a560)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
**Symbols:**

```
ffffffff8170a560-ffffffff8170a68e: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727320)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
**Symbols:**

```
ffffffff81727320-ffffffff8172744e: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170ad60)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
**Symbols:**

```
ffffffff8170ad60-ffffffff8170ae8e: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:692
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
**Symbols:**

```
ffffffff81786cb0-ffffffff81786e09: detach_buf_split (STB_LOCAL)
ffffffff81cf47aa-ffffffff81cf47d9: detach_buf_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:684
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
**Symbols:**

```
ffffffff818bdc30-ffffffff818bdd7a: detach_buf_split (STB_LOCAL)
ffffffff81ebc8b3-ffffffff81ebc8c7: detach_buf_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:731
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
**Symbols:**

```
ffffffff81a0c7c0-ffffffff81a0c922: detach_buf_split (STB_LOCAL)
ffffffff82093c0e-ffffffff82093c22: detach_buf_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:737
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
**Symbols:**

```
ffffffff81a554c0-ffffffff81a55622: detach_buf_split (STB_LOCAL)
ffffffff821148f6-ffffffff8211490a: detach_buf_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:765
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
```
**Symbols:**

```
ffffffff81aa6520-ffffffff81aa669a: detach_buf_split (STB_LOCAL)
ffffffff821f24f8-ffffffff821f2521: detach_buf_split.cold (STB_LOCAL)
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
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010822d00)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffff800010822d00-ffff800010822e80: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c09408a4)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
c09408a4-c0940a1c: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cde50)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
c0000000008cde50-c0000000008ce064: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe0005196c4)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffe0005196c4-ffffffe000519802: detach_buf_split (STB_LOCAL)
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
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81620f30)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff81620f30-ffffffff8162105e: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81615580)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff81615580-ffffffff816156ae: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164eed0)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff8164eed0-ffffffff8164effe: detach_buf_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void detach_buf_split(struct vring_virtqueue *vq, unsigned int head, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81669560)
Location: drivers/virtio/virtio_ring.c:620
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
**Symbols:**

```
ffffffff81669560-ffffffff8166968e: detach_buf_split (STB_LOCAL)
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
