# Function: <code>vring_unmap_extra_packed</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vring_unmap_extra_packed(const struct vring_virtqueue *vq, struct vring_desc_extra *extra);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bd3ab)
Location: drivers/virtio/virtio_ring.c:988
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff818bd370-ffffffff818bd3db: vring_unmap_extra_packed (STB_LOCAL)
ffffffff81ebc612-ffffffff81ebc627: vring_unmap_extra_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vring_unmap_extra_packed(const struct vring_virtqueue *vq, struct vring_desc_extra *extra);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0c20b)
Location: drivers/virtio/virtio_ring.c:1173
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81a0c1d0-ffffffff81a0c23b: vring_unmap_extra_packed (STB_LOCAL)
ffffffff82093b29-ffffffff82093b3e: vring_unmap_extra_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vring_unmap_extra_packed(const struct vring_virtqueue *vq, const struct vring_desc_extra *extra);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a5511e)
Location: drivers/virtio/virtio_ring.c:1193
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81a550e0-ffffffff81a5514a: vring_unmap_extra_packed (STB_LOCAL)
ffffffff8211485d-ffffffff82114872: vring_unmap_extra_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vring_unmap_extra_packed(const struct vring_virtqueue *vq, const struct vring_desc_extra *extra);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1223
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81aa5d10-ffffffff81aa5d90: vring_unmap_extra_packed (STB_LOCAL)
ffffffff821f2328-ffffffff821f2352: vring_unmap_extra_packed.cold (STB_LOCAL)
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
<code>struct vring_desc_extra *extra</code> ➡️ <code>const struct vring_desc_extra *extra</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
