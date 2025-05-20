# Function: <code>vring_create_virtqueue_dma</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue_dma(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a57be0)
Location: drivers/virtio/virtio_ring.c:2593
Inline: False
```
**Symbols:**

```
ffffffff81a57be0-ffffffff81a57c72: vring_create_virtqueue_dma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue_dma(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name, struct device *dma_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa9140)
Location: drivers/virtio/virtio_ring.c:2689
Inline: False
```
**Symbols:**

```
ffffffff81aa9140-ffffffff81aa91d2: vring_create_virtqueue_dma (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
