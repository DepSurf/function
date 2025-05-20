# Function: <code>virtqueue_add_indirect_packed</code>

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
In drivers/virtio/virtio_ring.c (ffffffff81606653)
Location: drivers/virtio/virtio_ring.c:975
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81638610)
Location: drivers/virtio/virtio_ring.c:979
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
**Symbols:**

```
ffffffff81638610-ffffffff81638934: virtqueue_add_indirect_packed (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (ffffffff8165c93a)
Location: drivers/virtio/virtio_ring.c:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b4f0)
Location: drivers/virtio/virtio_ring.c:979
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff8170b4f0-ffffffff8170b85f: virtqueue_add_indirect_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81728350)
Location: drivers/virtio/virtio_ring.c:979
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81728350-ffffffff817286c4: virtqueue_add_indirect_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170bb10)
Location: drivers/virtio/virtio_ring.c:979
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff8170bb10-ffffffff8170be1b: virtqueue_add_indirect_packed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1052
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81787d60-ffffffff817880d6: virtqueue_add_indirect_packed (STB_LOCAL)
ffffffff81cf4b64-ffffffff81cf4c0a: virtqueue_add_indirect_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1045
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff818bf360-ffffffff818bf6cd: virtqueue_add_indirect_packed (STB_LOCAL)
ffffffff81ebcc5e-ffffffff81ebcd20: virtqueue_add_indirect_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1230
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81a0f180-ffffffff81a0f50f: virtqueue_add_indirect_packed (STB_LOCAL)
ffffffff820941e4-ffffffff820942a6: virtqueue_add_indirect_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1250
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81a58250-ffffffff81a585ca: virtqueue_add_indirect_packed (STB_LOCAL)
ffffffff82114f44-ffffffff82115006: virtqueue_add_indirect_packed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1283
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
```
**Symbols:**

```
ffffffff81aa95c0-ffffffff81aa9977: virtqueue_add_indirect_packed (STB_LOCAL)
ffffffff821f2b86-ffffffff821f2c39: virtqueue_add_indirect_packed.cold (STB_LOCAL)
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
int virtqueue_add_indirect_packed(struct vring_virtqueue *vq, struct scatterlist **sgs, unsigned int total_sg, unsigned int out_sgs, unsigned int in_sgs, void *data, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff8000108236d0)
Location: drivers/virtio/virtio_ring.c:979
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
**Symbols:**

```
ffff8000108236d0-ffff800010823a64: virtqueue_add_indirect_packed (STB_LOCAL)
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
In drivers/virtio/virtio_ring.c (c0942474)
Location: drivers/virtio/virtio_ring.c:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
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
In drivers/virtio/virtio_ring.c (c0000000008d0030)
Location: drivers/virtio/virtio_ring.c:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
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
In drivers/virtio/virtio_ring.c (ffffffe00051a8be)
Location: drivers/virtio/virtio_ring.c:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
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
In drivers/virtio/virtio_ring.c (ffffffff816227da)
Location: drivers/virtio/virtio_ring.c:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
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
In drivers/virtio/virtio_ring.c (ffffffff81616e2a)
Location: drivers/virtio/virtio_ring.c:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
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
In drivers/virtio/virtio_ring.c (ffffffff8165077a)
Location: drivers/virtio/virtio_ring.c:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
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
In drivers/virtio/virtio_ring.c (ffffffff8166ae0a)
Location: drivers/virtio/virtio_ring.c:979
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
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
<b>Arch</b>
<ul>
</ul>
