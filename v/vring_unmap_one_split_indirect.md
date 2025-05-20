# Function: <code>vring_unmap_one_split_indirect</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81786d9c)
Location: drivers/virtio/virtio_ring.c:372
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81786b70-ffffffff81786ba9: vring_unmap_one_split_indirect.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue *vq, struct vring_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bdbe9)
Location: drivers/virtio/virtio_ring.c:372
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff818bdbc0-ffffffff818bdc28: vring_unmap_one_split_indirect (STB_LOCAL)
ffffffff81ebc89e-ffffffff81ebc8b3: vring_unmap_one_split_indirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue *vq, struct vring_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0c769)
Location: drivers/virtio/virtio_ring.c:419
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81a0c740-ffffffff81a0c7a8: vring_unmap_one_split_indirect (STB_LOCAL)
ffffffff82093bf9-ffffffff82093c0e: vring_unmap_one_split_indirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue *vq, const struct vring_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a55469)
Location: drivers/virtio/virtio_ring.c:425
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81a55440-ffffffff81a554a5: vring_unmap_one_split_indirect (STB_LOCAL)
ffffffff821148e1-ffffffff821148f6: vring_unmap_one_split_indirect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vring_unmap_one_split_indirect(const struct vring_virtqueue *vq, const struct vring_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa64c9)
Location: drivers/virtio/virtio_ring.c:443
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
**Symbols:**

```
ffffffff81aa64a0-ffffffff81aa6505: vring_unmap_one_split_indirect (STB_LOCAL)
ffffffff821f24e3-ffffffff821f24f8: vring_unmap_one_split_indirect.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vring_desc *desc</code> ➡️ <code>const struct vring_desc *desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
