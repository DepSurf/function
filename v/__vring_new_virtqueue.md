# Function: <code>__vring_new_virtqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f630)
Location: drivers/virtio/virtio_ring.c:912
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8150f630-ffffffff8150f7af: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b7d0)
Location: drivers/virtio/virtio_ring.c:915
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8153b7d0-ffffffff8153b953: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f120)
Location: drivers/virtio/virtio_ring.c:958
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
```
**Symbols:**

```
ffffffff8154f120-ffffffff8154f29f: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b28e0)
Location: drivers/virtio/virtio_ring.c:957
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
```
**Symbols:**

```
ffffffff815b28e0-ffffffff815b2a5f: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ead10)
Location: drivers/virtio/virtio_ring.c:956
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
```
**Symbols:**

```
ffffffff815ead10-ffffffff815eae96: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81605b40)
Location: drivers/virtio/virtio_ring.c:2048
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81605b40-ffffffff81605d68: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81637cc0)
Location: drivers/virtio/virtio_ring.c:2054
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81637cc0-ffffffff81637eea: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659ab0)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81659ab0-ffffffff81659cda: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b060)
Location: drivers/virtio/virtio_ring.c:2056
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff8170b060-ffffffff8170b283: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81727eb0)
Location: drivers/virtio/virtio_ring.c:2056
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81727eb0-ffffffff817280e6: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170c3d0)
Location: drivers/virtio/virtio_ring.c:2058
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff8170c3d0-ffffffff8170c61d: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817887d0)
Location: drivers/virtio/virtio_ring.c:2172
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff817887d0-ffffffff81788a09: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bedf0)
Location: drivers/virtio/virtio_ring.c:2183
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff818bedf0-ffffffff818bf022: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring_virtqueue_split *vring_split, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2477
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81a0e480-ffffffff81a0e6c5: __vring_new_virtqueue (STB_LOCAL)
ffffffff820940da-ffffffff82094104: __vring_new_virtqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring_virtqueue_split *vring_split, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2508
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81a573d0-ffffffff81a5761d: __vring_new_virtqueue (STB_LOCAL)
ffffffff82114e2c-ffffffff82114e56: __vring_new_virtqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring_virtqueue_split *vring_split, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name, struct device *dma_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2602
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_split
```
**Symbols:**

```
ffffffff81aa8bc0-ffffffff81aa8e47: __vring_new_virtqueue (STB_LOCAL)
ffffffff821f2ab4-ffffffff821f2ade: __vring_new_virtqueue.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010823428)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffff800010823428-ffff8000108235f0: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0940f80)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
c0940f80-c0941190: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cbe80)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
c0000000008cbe80-c0000000008cc104: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000519c8a)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffe000519c8a-ffffffe000519e1e: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f950)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8161f950-ffffffff8161fb7a: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81613ef0)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81613ef0-ffffffff8161410d: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d8f0)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff8164d8f0-ffffffff8164db1a: __vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct virtqueue *__vring_new_virtqueue(unsigned int index, struct vring vring, struct virtio_device *vdev, bool weak_barriers, bool context, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81667f80)
Location: drivers/virtio/virtio_ring.c:2053
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
```
**Symbols:**

```
ffffffff81667f80-ffffffff816681aa: __vring_new_virtqueue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool context</code>
</li>
<li>
<b>Param reordered. </b>
<code>index, vring, vdev, weak_barriers, notify, callback, name</code> ➡️ <code>index, vring, vdev, weak_barriers, context, notify, callback, name</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vring_virtqueue_split *vring_split</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vring vring</code>
</li>
</ul>
</details>
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
