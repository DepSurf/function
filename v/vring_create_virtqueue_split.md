# Function: <code>vring_create_virtqueue_split</code>

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
In drivers/virtio/virtio_ring.c (ffffffff81605e43)
Location: drivers/virtio/virtio_ring.c:843
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffff81637fc4)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffff81659db4)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:845
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8170b300-ffffffff8170b4f0: vring_create_virtqueue_split (STB_LOCAL)
ffffffff8170c2fc-ffffffff8170c315: vring_create_virtqueue_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:845
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81728160-ffffffff81728350: vring_create_virtqueue_split (STB_LOCAL)
ffffffff81c0465b-ffffffff81c04674: vring_create_virtqueue_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:845
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8170c690-ffffffff8170c87c: vring_create_virtqueue_split (STB_LOCAL)
ffffffff81bf6258-ffffffff81bf6271: vring_create_virtqueue_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:918
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81788a80-ffffffff81788c6c: vring_create_virtqueue_split (STB_LOCAL)
ffffffff81cf4d69-ffffffff81cf4d82: vring_create_virtqueue_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct virtqueue *vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:910
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff818bf0d0-ffffffff818bf354: vring_create_virtqueue_split (STB_LOCAL)
ffffffff81ebcc47-ffffffff81ebcc5e: vring_create_virtqueue_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0eb8a)
Location: drivers/virtio/virtio_ring.c:1093
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a57730)
Location: drivers/virtio/virtio_ring.c:1111
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_dma
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81a57730-ffffffff81a5784d: vring_create_virtqueue_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct virtqueue *vring_create_virtqueue_split(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool may_reduce_num, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa8f60)
Location: drivers/virtio/virtio_ring.c:1141
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_dma
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81aa8f60-ffffffff81aa907d: vring_create_virtqueue_split (STB_LOCAL)
```
</details>
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
In drivers/virtio/virtio_ring.c (ffff8000108242f4)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (c09415d4)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (c0000000008cc230)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffe00051a190)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffff8161fc54)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffff816141e4)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffff8164dbf4)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffff81668284)
Location: drivers/virtio/virtio_ring.c:845
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
