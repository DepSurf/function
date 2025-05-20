# Function: <code>vring_use_dma_api</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8150f0f0)
Location: drivers/virtio/virtio_ring.c:145
Inline: True
```
**Symbols:**

```
ffffffff8150f0f0-ffffffff8150f114: vring_use_dma_api (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153b250)
Location: drivers/virtio/virtio_ring.c:145
Inline: True
```
**Symbols:**

```
ffffffff8153b250-ffffffff8153b274: vring_use_dma_api (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8154eae0)
Location: drivers/virtio/virtio_ring.c:145
Inline: True
```
**Symbols:**

```
ffffffff8154eae0-ffffffff8154eb04: vring_use_dma_api (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b2290)
Location: drivers/virtio/virtio_ring.c:145
Inline: True
```
**Symbols:**

```
ffffffff815b2290-ffffffff815b22b4: vring_use_dma_api (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ea6f0)
Location: drivers/virtio/virtio_ring.c:144
Inline: True
```
**Symbols:**

```
ffffffff815ea6f0-ffffffff815ea714: vring_use_dma_api (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81604da0)
Location: drivers/virtio/virtio_ring.c:254
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
**Symbols:**

```
ffffffff81604da0-ffffffff81604dc4: vring_use_dma_api (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816376b0)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
**Symbols:**

```
ffffffff816376b0-ffffffff816376d4: vring_use_dma_api (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81659490)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
**Symbols:**

```
ffffffff81659490-ffffffff816594b4: vring_use_dma_api (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (ffffffff8170b131)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
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
In drivers/virtio/virtio_ring.c (ffffffff81727f83)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
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
In drivers/virtio/virtio_ring.c (ffffffff8170c49f)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81788895)
Location: drivers/virtio/virtio_ring.c:246
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818beeb3)
Location: drivers/virtio/virtio_ring.c:246
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
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
In drivers/virtio/virtio_ring.c (ffffffff81a0e523)
Location: drivers/virtio/virtio_ring.c:268
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a5747e)
Location: drivers/virtio/virtio_ring.c:272
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa8c9a)
Location: drivers/virtio/virtio_ring.c:280
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010821c50)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
**Symbols:**

```
ffff800010821c50-ffff800010821c9c: vring_use_dma_api (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (c094105c)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
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
In drivers/virtio/virtio_ring.c (c0000000008cbf78)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
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
In drivers/virtio/virtio_ring.c (ffffffe000519cf6)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161f330)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
**Symbols:**

```
ffffffff8161f330-ffffffff8161f354: vring_use_dma_api (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (ffffffff81613fdf)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164d2d0)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
**Symbols:**

```
ffffffff8164d2d0-ffffffff8164d2f4: vring_use_dma_api (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool vring_use_dma_api(struct virtio_device *vdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81667960)
Location: drivers/virtio/virtio_ring.c:241
Inline: True
Direct callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
**Symbols:**

```
ffffffff81667960-ffffffff81667984: vring_use_dma_api (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
