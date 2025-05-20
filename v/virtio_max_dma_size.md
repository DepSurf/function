# Function: <code>virtio_max_dma_size</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816376e0)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff816376e0-ffffffff8163770d: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816594c0)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff816594c0-ffffffff816594ed: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170a1b0)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff8170a1b0-ffffffff8170a1df: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817276e0)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff817276e0-ffffffff8172770f: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b320)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff8170b320-ffffffff8170b34f: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817873a0)
Location: drivers/virtio/virtio_ring.c:266
Inline: True
```
**Symbols:**

```
ffffffff817873a0-ffffffff817873cf: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818be380)
Location: drivers/virtio/virtio_ring.c:266
Inline: True
```
**Symbols:**

```
ffffffff818be380-ffffffff818be3bf: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0d410)
Location: drivers/virtio/virtio_ring.c:288
Inline: True
```
**Symbols:**

```
ffffffff81a0d410-ffffffff81a0d44f: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
size_t virtio_max_dma_size(const struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a56310)
Location: drivers/virtio/virtio_ring.c:292
Inline: True
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
```
**Symbols:**

```
ffffffff81a56310-ffffffff81a5634f: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
size_t virtio_max_dma_size(const struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa7430)
Location: drivers/virtio/virtio_ring.c:300
Inline: True
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
```
**Symbols:**

```
ffffffff81aa7430-ffffffff81aa746f: virtio_max_dma_size (STB_GLOBAL)
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
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010821ca0)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffff800010821ca0-ffff800010821cec: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093f7c8)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
c093f7c8-c093f804: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cb850)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
c0000000008cb850-c0000000008cb8a8: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000518828)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffe000518828-ffffffe000518862: virtio_max_dma_size (STB_GLOBAL)
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
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f360)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff8161f360-ffffffff8161f38d: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81613950)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff81613950-ffffffff81613975: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d300)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff8164d300-ffffffff8164d32d: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t virtio_max_dma_size(struct virtio_device *vdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81667990)
Location: drivers/virtio/virtio_ring.c:261
Inline: False
```
**Symbols:**

```
ffffffff81667990-ffffffff816679bd: virtio_max_dma_size (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct virtio_device *vdev</code> ➡️ <code>const struct virtio_device *vdev</code>
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
