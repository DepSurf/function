# Function: <code>vring_unmap_one_split</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81606c6a)
Location: drivers/virtio/virtio_ring.c:369
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffffffff81605470-ffffffff816054d5: vring_unmap_one_split.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8163a58a)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffffffff81638d20-ffffffff81638d88: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165c87d)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffffffff8165aa80-ffffffff8165aae8: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a633)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff8170a4f0-ffffffff8170a558: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817273f3)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff817272e0-ffffffff8172731a: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170ae33)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff8170abf0-ffffffff8170ac29: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int vring_unmap_one_split(const struct vring_virtqueue *vq, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:397
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff817862e0-ffffffff8178634e: vring_unmap_one_split (STB_LOCAL)
ffffffff81cf44a6-ffffffff81cf44bb: vring_unmap_one_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int vring_unmap_one_split(const struct vring_virtqueue *vq, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:389
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff818bd0b0-ffffffff818bd12d: vring_unmap_one_split (STB_LOCAL)
ffffffff81ebc578-ffffffff81ebc58d: vring_unmap_one_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int vring_unmap_one_split(const struct vring_virtqueue *vq, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:436
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81a0bed0-ffffffff81a0bf4d: vring_unmap_one_split (STB_LOCAL)
ffffffff82093a8f-ffffffff82093aa4: vring_unmap_one_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int vring_unmap_one_split(const struct vring_virtqueue *vq, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:442
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81a54df0-ffffffff81a54e6c: vring_unmap_one_split (STB_LOCAL)
ffffffff821147cb-ffffffff821147e0: vring_unmap_one_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int vring_unmap_one_split(const struct vring_virtqueue *vq, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:460
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81aa5da0-ffffffff81aa5e2e: vring_unmap_one_split (STB_LOCAL)
ffffffff821f2352-ffffffff821f237c: vring_unmap_one_split.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff8000108257a8)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffff800010822760-ffff8000108227d8: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0942398)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
c0940820-c09408a4: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008d0294)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
c0000000008cd660-c0000000008cd714: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051a7f4)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffffffe000519662-ffffffe0005196c4: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8162271d)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffffffff81620920-ffffffff81620988: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81616d6d)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffffffff81614f70-ffffffff81614fd8: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816506bd)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffffffff8164e8c0-ffffffff8164e928: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8166ad4d)
Location: drivers/virtio/virtio_ring.c:367
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
**Symbols:**

```
ffffffff81668f50-ffffffff81668fb8: vring_unmap_one_split.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
