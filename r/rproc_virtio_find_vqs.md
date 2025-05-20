# Function: <code>rproc_virtio_find_vqs</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
ffffffff818f6d90-ffffffff818f7063: rproc_virtio_find_vqs (STB_LOCAL)
ffffffff818f7396-ffffffff818f73c7: rproc_virtio_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cd030)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
ffffffff819cd030-ffffffff819cd114: rproc_virtio_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cc880)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
ffffffff819cc880-ffffffff819cc964: rproc_virtio_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819b1a30)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
ffffffff819b1a30-ffffffff819b1b14: rproc_virtio_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
ffffffff81a602b0-ffffffff81a603b6: rproc_virtio_find_vqs (STB_LOCAL)
ffffffff81d32b25-ffffffff81d32b57: rproc_virtio_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:155
Inline: False
```
**Symbols:**

```
ffffffff81bd0780-ffffffff81bd0895: rproc_virtio_find_vqs (STB_LOCAL)
ffffffff81eff002-ffffffff81eff032: rproc_virtio_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:183
Inline: False
```
**Symbols:**

```
ffffffff81d7baa0-ffffffff81d7bbb5: rproc_virtio_find_vqs (STB_LOCAL)
ffffffff820aa33d-ffffffff820aa36d: rproc_virtio_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:183
Inline: False
```
**Symbols:**

```
ffffffff81de9c60-ffffffff81de9d75: rproc_virtio_find_vqs (STB_LOCAL)
ffffffff8212b83c-ffffffff8212b86c: rproc_virtio_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:183
Inline: False
```
**Symbols:**

```
ffffffff81e9fea0-ffffffff81e9ffb5: rproc_virtio_find_vqs (STB_LOCAL)
ffffffff8220d463-ffffffff8220d493: rproc_virtio_find_vqs.cold (STB_LOCAL)
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
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffff800010b83008)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
ffff800010b83008-ffff800010b83320: rproc_virtio_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (c0c6631c)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
c0c6631c-c0c665e0: rproc_virtio_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (c000000000c60390)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
c000000000c60390-c000000000c60794: rproc_virtio_find_vqs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
ffffffff818980c0-ffffffff81898393: rproc_virtio_find_vqs (STB_LOCAL)
ffffffff818986c6-ffffffff818986f7: rproc_virtio_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rproc_virtio_find_vqs(struct virtio_device *vdev, unsigned int nvqs, struct virtqueue **vqs, vq_callback_t **callbacks, const const char * *names, const bool *ctx, struct irq_affinity *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:143
Inline: False
```
**Symbols:**

```
ffffffff81908820-ffffffff81908af3: rproc_virtio_find_vqs (STB_LOCAL)
ffffffff81908e26-ffffffff81908e57: rproc_virtio_find_vqs.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
