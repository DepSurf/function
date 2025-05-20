# Function: <code>vring_new_virtqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bf400)
Location: drivers/virtio/virtio_ring.c:723
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
**Symbols:**

```
ffffffff814bf400-ffffffff814bf597: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f7b0)
Location: drivers/virtio/virtio_ring.c:1073
Inline: False
```
**Symbols:**

```
ffffffff8150f7b0-ffffffff8150f814: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b960)
Location: drivers/virtio/virtio_ring.c:1077
Inline: False
```
**Symbols:**

```
ffffffff8153b960-ffffffff8153b9c4: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154f2a0)
Location: drivers/virtio/virtio_ring.c:1123
Inline: False
```
**Symbols:**

```
ffffffff8154f2a0-ffffffff8154f300: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2a60)
Location: drivers/virtio/virtio_ring.c:1122
Inline: False
```
**Symbols:**

```
ffffffff815b2a60-ffffffff815b2ac0: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815eaea0)
Location: drivers/virtio/virtio_ring.c:1121
Inline: False
```
**Symbols:**

```
ffffffff815eaea0-ffffffff815eaf00: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81605d70)
Location: drivers/virtio/virtio_ring.c:2151
Inline: False
```
**Symbols:**

```
ffffffff81605d70-ffffffff81605dda: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81637ef0)
Location: drivers/virtio/virtio_ring.c:2157
Inline: False
```
**Symbols:**

```
ffffffff81637ef0-ffffffff81637f5d: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659ce0)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81659ce0-ffffffff81659d4d: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b290)
Location: drivers/virtio/virtio_ring.c:2159
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff8170b290-ffffffff8170b2f7: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817280f0)
Location: drivers/virtio/virtio_ring.c:2159
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff817280f0-ffffffff81728157: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170c620)
Location: drivers/virtio/virtio_ring.c:2163
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff8170c620-ffffffff8170c688: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81788a10)
Location: drivers/virtio/virtio_ring.c:2283
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81788a10-ffffffff81788a78: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bf030)
Location: drivers/virtio/virtio_ring.c:2298
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff818bf030-ffffffff818bf0c9: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0e6e0)
Location: drivers/virtio/virtio_ring.c:2630
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81a0e6e0-ffffffff81a0e7bd: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a57630)
Location: drivers/virtio/virtio_ring.c:2688
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81a57630-ffffffff81a57713: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa8e60)
Location: drivers/virtio/virtio_ring.c:2849
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rp_find_vq
```
**Symbols:**

```
ffffffff81aa8e60-ffffffff81aa8f43: vring_new_virtqueue (STB_GLOBAL)
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
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff8000108235f0)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffff8000108235f0-ffff8000108236d0: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0941190)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
c0941190-c094122c: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cc110)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
c0000000008cc110-c0000000008cc1b8: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000519e1e)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
```
**Symbols:**

```
ffffffe000519e1e-ffffffe000519ed6: vring_new_virtqueue (STB_GLOBAL)
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
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161fb80)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff8161fb80-ffffffff8161fbed: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81614110)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
```
**Symbols:**

```
ffffffff81614110-ffffffff8161417d: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164db20)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
```
**Symbols:**

```
ffffffff8164db20-ffffffff8164db8d: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct virtqueue *vring_new_virtqueue(unsigned int index, unsigned int num, unsigned int vring_align, struct virtio_device *vdev, bool weak_barriers, bool context, void *pages, bool (*notify)(struct virtqueue *), void (*callback)(struct virtqueue *), const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816681b0)
Location: drivers/virtio/virtio_ring.c:2156
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff816681b0-ffffffff8166821d: vring_new_virtqueue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<code>index, num, vring_align, vdev, weak_barriers, pages, notify, callback, name</code> ➡️ <code>index, num, vring_align, vdev, weak_barriers, context, pages, notify, callback, name</code>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
