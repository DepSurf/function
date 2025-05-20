# Function: <code>virtqueue_get_buf_ctx_split</code>

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
In drivers/virtio/virtio_ring.c (ffffffff8160596a)
Location: drivers/virtio/virtio_ring.c:676
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (ffffffff8163ab81)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (ffffffff8165d041)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_split(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:678
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8170a690-ffffffff8170a771: virtqueue_get_buf_ctx_split (STB_LOCAL)
ffffffff8170c268-ffffffff8170c2b3: virtqueue_get_buf_ctx_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_split(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:678
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81727500-ffffffff817275d9: virtqueue_get_buf_ctx_split (STB_LOCAL)
ffffffff81c04610-ffffffff81c0465b: virtqueue_get_buf_ctx_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_split(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:678
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8170af40-ffffffff8170b019: virtqueue_get_buf_ctx_split (STB_LOCAL)
ffffffff81bf620d-ffffffff81bf6258: virtqueue_get_buf_ctx_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_split(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:748
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81786e10-ffffffff81786f2d: virtqueue_get_buf_ctx_split (STB_LOCAL)
ffffffff81cf47d9-ffffffff81cf4875: virtqueue_get_buf_ctx_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_split(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:740
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff818bde40-ffffffff818bdf61: virtqueue_get_buf_ctx_split (STB_LOCAL)
ffffffff81ebc8dc-ffffffff81ebc975: virtqueue_get_buf_ctx_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_split(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:787
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81a0c940-ffffffff81a0caa7: virtqueue_get_buf_ctx_split (STB_LOCAL)
ffffffff82093c22-ffffffff82093c75: virtqueue_get_buf_ctx_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_split(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:793
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81a55640-ffffffff81a557a4: virtqueue_get_buf_ctx_split (STB_LOCAL)
ffffffff8211490a-ffffffff8211495d: virtqueue_get_buf_ctx_split.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_split(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:823
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81aa66b0-ffffffff81aa6814: virtqueue_get_buf_ctx_split (STB_LOCAL)
ffffffff821f2521-ffffffff821f2574: virtqueue_get_buf_ctx_split.cold (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (ffff800010823240)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (c0940de0)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (c0000000008d0b70)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (ffffffe000519a66)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (ffffffff81622ee1)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (ffffffff81617531)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (ffffffff81650e81)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
In drivers/virtio/virtio_ring.c (ffffffff8166b511)
Location: drivers/virtio/virtio_ring.c:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
