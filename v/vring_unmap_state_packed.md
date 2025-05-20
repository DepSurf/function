# Function: <code>vring_unmap_state_packed</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8160576a)
Location: drivers/virtio/virtio_ring.c:910
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8163a946)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165ce06)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a893)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81726ddc)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170aa50)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vring_unmap_state_packed(const struct vring_virtqueue *vq, struct vring_desc_extra *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8178664b)
Location: drivers/virtio/virtio_ring.c:987
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81786610-ffffffff8178666a: vring_unmap_state_packed (STB_LOCAL)
ffffffff81cf4577-ffffffff81cf458c: vring_unmap_state_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010822fa8)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0940b3c)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008d0890)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe0005198fa)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81622ca6)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816172f6)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81650c46)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8166b2d6)
Location: drivers/virtio/virtio_ring.c:914
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:detach_buf_packed
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
