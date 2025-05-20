# Function: <code>vring_alloc_state_extra_split</code>

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
int vring_alloc_state_extra_split(struct vring_virtqueue_split *vring_split);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0e3f0)
Location: drivers/virtio/virtio_ring.c:1008
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
**Symbols:**

```
ffffffff81a0e3f0-ffffffff81a0e46d: vring_alloc_state_extra_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vring_alloc_state_extra_split(struct vring_virtqueue_split *vring_split);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a57340)
Location: drivers/virtio/virtio_ring.c:1022
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
**Symbols:**

```
ffffffff81a57340-ffffffff81a573bd: vring_alloc_state_extra_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vring_alloc_state_extra_split(struct vring_virtqueue_split *vring_split);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa8b30)
Location: drivers/virtio/virtio_ring.c:1052
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
**Symbols:**

```
ffffffff81aa8b30-ffffffff81aa8bad: vring_alloc_state_extra_split (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
