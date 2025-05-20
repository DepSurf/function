# Function: <code>vring_alloc_state_extra_packed</code>

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
int vring_alloc_state_extra_packed(struct vring_virtqueue_packed *vring_packed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0e7d0)
Location: drivers/virtio/virtio_ring.c:1916
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
```
**Symbols:**

```
ffffffff81a0e7d0-ffffffff81a0e84d: vring_alloc_state_extra_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vring_alloc_state_extra_packed(struct vring_virtqueue_packed *vring_packed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a57860)
Location: drivers/virtio/virtio_ring.c:1951
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
```
**Symbols:**

```
ffffffff81a57860-ffffffff81a578dd: vring_alloc_state_extra_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vring_alloc_state_extra_packed(struct vring_virtqueue_packed *vring_packed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa8770)
Location: drivers/virtio/virtio_ring.c:1989
Inline: False
```
**Symbols:**

```
ffffffff81aa8770-ffffffff81aa87ed: vring_alloc_state_extra_packed (STB_LOCAL)
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
