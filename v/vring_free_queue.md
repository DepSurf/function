# Function: <code>vring_free_queue</code>

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
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f240)
Location: drivers/virtio/virtio_ring.c:1001
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8150f240-ffffffff8150f2f6: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b390)
Location: drivers/virtio/virtio_ring.c:1005
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8153b390-ffffffff8153b446: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154ec20)
Location: drivers/virtio/virtio_ring.c:1050
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
```
**Symbols:**

```
ffffffff8154ec20-ffffffff8154ecbd: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b23c0)
Location: drivers/virtio/virtio_ring.c:1049
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
```
**Symbols:**

```
ffffffff815b23c0-ffffffff815b2460: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ea820)
Location: drivers/virtio/virtio_ring.c:1048
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
```
**Symbols:**

```
ffffffff815ea820-ffffffff815ea8c0: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81604e70)
Location: drivers/virtio/virtio_ring.c:307
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81604e70-ffffffff81604ed3: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816377b0)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff816377b0-ffffffff81637813: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659590)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81659590-ffffffff816595f3: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a1e0)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff8170a1e0-ffffffff8170a222: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727710)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81727710-ffffffff81727752: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b350)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff8170b350-ffffffff8170b392: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817873d0)
Location: drivers/virtio/virtio_ring.c:310
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff817873d0-ffffffff81787412: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818be3c0)
Location: drivers/virtio/virtio_ring.c:310
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff818be3c0-ffffffff818be424: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0d460)
Location: drivers/virtio/virtio_ring.c:332
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_free_packed
  - drivers/virtio/virtio_ring.c:vring_free_packed
  - drivers/virtio/virtio_ring.c:vring_free_packed
```
**Symbols:**

```
ffffffff81a0d460-ffffffff81a0d4c4: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a56360)
Location: drivers/virtio/virtio_ring.c:337
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:vring_free_packed
  - drivers/virtio/virtio_ring.c:vring_free_packed
  - drivers/virtio/virtio_ring.c:vring_free_packed
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81a56360-ffffffff81a563c6: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa7480)
Location: drivers/virtio/virtio_ring.c:345
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free
  - drivers/virtio/virtio_ring.c:vring_free_packed
  - drivers/virtio/virtio_ring.c:vring_free_packed
  - drivers/virtio/virtio_ring.c:vring_free_packed
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81aa7480-ffffffff81aa74e6: vring_free_queue (STB_LOCAL)
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
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010821db8)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffff800010821db8-ffff800010821e38: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093f880)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
c093f880-c093f8e8: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cb950)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
c0000000008cb950-c0000000008cb9c0: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe0005188f0)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffe0005188f0-ffffffe000518966: vring_free_queue (STB_LOCAL)
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
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f430)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8161f430-ffffffff8161f493: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81613a00)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81613a00-ffffffff81613a38: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d3d0)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8164d3d0-ffffffff8164d433: vring_free_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void vring_free_queue(struct virtio_device *vdev, size_t size, void *queue, dma_addr_t dma_handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81667a60)
Location: drivers/virtio/virtio_ring.c:305
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_del_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81667a60-ffffffff81667ac3: vring_free_queue (STB_LOCAL)
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
