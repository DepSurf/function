# Function: <code>vring_alloc_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f370)
Location: drivers/virtio/virtio_ring.c:969
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8150f370-ffffffff8150f474: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b4c0)
Location: drivers/virtio/virtio_ring.c:973
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8153b4c0-ffffffff8153b5c4: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154ed20)
Location: drivers/virtio/virtio_ring.c:1018
Inline: True
```
**Symbols:**

```
ffffffff8154ed20-ffffffff8154ee24: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b24c0)
Location: drivers/virtio/virtio_ring.c:1017
Inline: True
```
**Symbols:**

```
ffffffff815b24c0-ffffffff815b25c7: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ea920)
Location: drivers/virtio/virtio_ring.c:1016
Inline: True
```
**Symbols:**

```
ffffffff815ea920-ffffffff815eaa53: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81604dd0)
Location: drivers/virtio/virtio_ring.c:274
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81604dd0-ffffffff81604e69: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81637710)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81637710-ffffffff816377aa: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816594f0)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff816594f0-ffffffff8165958a: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a330)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff8170a330-ffffffff8170a3b9: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727860)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81727860-ffffffff817278e9: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b3a0)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff8170b3a0-ffffffff8170b429: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81787420)
Location: drivers/virtio/virtio_ring.c:277
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81787420-ffffffff817874a9: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818be590)
Location: drivers/virtio/virtio_ring.c:277
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff818be590-ffffffff818be635: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0d710)
Location: drivers/virtio/virtio_ring.c:299
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
**Symbols:**

```
ffffffff81a0d710-ffffffff81a0d7b5: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a56650)
Location: drivers/virtio/virtio_ring.c:303
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
**Symbols:**

```
ffffffff81a56650-ffffffff81a566f7: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa7770)
Location: drivers/virtio/virtio_ring.c:311
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_packed
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
  - drivers/virtio/virtio_ring.c:vring_alloc_queue_split
```
**Symbols:**

```
ffffffff81aa7770-ffffffff81aa7817: vring_alloc_queue (STB_LOCAL)
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
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010821cf0)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffff800010821cf0-ffff800010821db8: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093f804)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
c093f804-c093f880: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cb8b0)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
c0000000008cb8b0-c0000000008cb948: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000518862)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffe000518862-ffffffe0005188f0: vring_alloc_queue (STB_LOCAL)
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
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f390)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8161f390-ffffffff8161f42a: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81613980)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81613980-ffffffff816139f8: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d330)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8164d330-ffffffff8164d3ca: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *vring_alloc_queue(struct virtio_device *vdev, size_t size, dma_addr_t *dma_handle, gfp_t flag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816679c0)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff816679c0-ffffffff81667a5a: vring_alloc_queue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dma_dev</code>
</li>
</ul>
</details>
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
