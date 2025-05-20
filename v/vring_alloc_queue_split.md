# Function: <code>vring_alloc_queue_split</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vring_alloc_queue_split(struct vring_virtqueue_split *vring_split, struct virtio_device *vdev, u32 num, unsigned int vring_align, bool may_reduce_num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0d900)
Location: drivers/virtio/virtio_ring.c:1045
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81a0d900-ffffffff81a0db07: vring_alloc_queue_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vring_alloc_queue_split(struct vring_virtqueue_split *vring_split, struct virtio_device *vdev, u32 num, unsigned int vring_align, bool may_reduce_num, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a56850)
Location: drivers/virtio/virtio_ring.c:1060
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81a56850-ffffffff81a56a5e: vring_alloc_queue_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vring_alloc_queue_split(struct vring_virtqueue_split *vring_split, struct virtio_device *vdev, u32 num, unsigned int vring_align, bool may_reduce_num, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa7970)
Location: drivers/virtio/virtio_ring.c:1090
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81aa7970-ffffffff81aa7b7e: vring_alloc_queue_split (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
