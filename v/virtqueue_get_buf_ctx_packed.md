# Function: <code>virtqueue_get_buf_ctx_packed</code>

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
In drivers/virtio/virtio_ring.c (ffffffff816058bf)
Location: drivers/virtio/virtio_ring.c:1341
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
In drivers/virtio/virtio_ring.c (ffffffff8163aabf)
Location: drivers/virtio/virtio_ring.c:1346
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
In drivers/virtio/virtio_ring.c (ffffffff8165cf7f)
Location: drivers/virtio/virtio_ring.c:1346
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
void *virtqueue_get_buf_ctx_packed(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1346
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8170aa00-ffffffff8170ab27: virtqueue_get_buf_ctx_packed (STB_LOCAL)
ffffffff8170c2b3-ffffffff8170c2fc: virtqueue_get_buf_ctx_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_packed(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1346
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81726e50-ffffffff81726f77: virtqueue_get_buf_ctx_packed (STB_LOCAL)
ffffffff81c045c7-ffffffff81c04610: virtqueue_get_buf_ctx_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_packed(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1346
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff8170aac0-ffffffff8170abe7: virtqueue_get_buf_ctx_packed (STB_LOCAL)
ffffffff81bf61c4-ffffffff81bf620d: virtqueue_get_buf_ctx_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_packed(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1432
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff817871a0-ffffffff81787345: virtqueue_get_buf_ctx_packed (STB_LOCAL)
ffffffff81cf48e4-ffffffff81cf49d4: virtqueue_get_buf_ctx_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_packed(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1430
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff818bd5e0-ffffffff818bd760: virtqueue_get_buf_ctx_packed (STB_LOCAL)
ffffffff81ebc67b-ffffffff81ebc71a: virtqueue_get_buf_ctx_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_packed(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1615
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81a0c470-ffffffff81a0c66f: virtqueue_get_buf_ctx_packed (STB_LOCAL)
ffffffff82093b92-ffffffff82093bde: virtqueue_get_buf_ctx_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_packed(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1635
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81a56080-ffffffff81a5627c: virtqueue_get_buf_ctx_packed (STB_LOCAL)
ffffffff82114bdd-ffffffff82114c29: virtqueue_get_buf_ctx_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *virtqueue_get_buf_ctx_packed(struct virtqueue *_vq, unsigned int *len, void **ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1673
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf
```
**Symbols:**

```
ffffffff81aa71a0-ffffffff81aa739c: virtqueue_get_buf_ctx_packed (STB_LOCAL)
ffffffff821f2809-ffffffff821f2855: virtqueue_get_buf_ctx_packed.cold (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (ffff800010823158)
Location: drivers/virtio/virtio_ring.c:1346
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
In drivers/virtio/virtio_ring.c (c0940ce4)
Location: drivers/virtio/virtio_ring.c:1346
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
In drivers/virtio/virtio_ring.c (c0000000008d0b30)
Location: drivers/virtio/virtio_ring.c:1346
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
In drivers/virtio/virtio_ring.c (ffffffe000519a36)
Location: drivers/virtio/virtio_ring.c:1346
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
In drivers/virtio/virtio_ring.c (ffffffff81622e1f)
Location: drivers/virtio/virtio_ring.c:1346
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
In drivers/virtio/virtio_ring.c (ffffffff8161746f)
Location: drivers/virtio/virtio_ring.c:1346
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
In drivers/virtio/virtio_ring.c (ffffffff81650dbf)
Location: drivers/virtio/virtio_ring.c:1346
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
In drivers/virtio/virtio_ring.c (ffffffff8166b44f)
Location: drivers/virtio/virtio_ring.c:1346
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
