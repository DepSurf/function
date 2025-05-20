# Function: <code>rp_find_vq</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff818f6f68)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct virtqueue *rp_find_vq(struct virtio_device *vdev, unsigned int id, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff819cce70-ffffffff819cd021: rp_find_vq (STB_LOCAL)
ffffffff819cd506-ffffffff819cd52f: rp_find_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct virtqueue *rp_find_vq(struct virtio_device *vdev, unsigned int id, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff819cc6c0-ffffffff819cc871: rp_find_vq (STB_LOCAL)
ffffffff81c2ee10-ffffffff81c2ee39: rp_find_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct virtqueue *rp_find_vq(struct virtio_device *vdev, unsigned int id, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff819b1870-ffffffff819b1a21: rp_find_vq (STB_LOCAL)
ffffffff81c210e3-ffffffff81c2110c: rp_find_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct virtqueue *rp_find_vq(struct virtio_device *vdev, unsigned int id, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81a5fff0-ffffffff81a601c7: rp_find_vq (STB_LOCAL)
ffffffff81d32ad2-ffffffff81d32afb: rp_find_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct virtqueue *rp_find_vq(struct virtio_device *vdev, unsigned int id, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: drivers/remoteproc/remoteproc_virtio.c:77
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81bd0470-ffffffff81bd0671: rp_find_vq (STB_LOCAL)
ffffffff81efefb0-ffffffff81efefd8: rp_find_vq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct virtqueue *rp_find_vq(struct virtio_device *vdev, unsigned int id, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7b880)
Location: drivers/remoteproc/remoteproc_virtio.c:103
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81d7b880-ffffffff81d7ba85: rp_find_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct virtqueue *rp_find_vq(struct virtio_device *vdev, unsigned int id, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81de9a40)
Location: drivers/remoteproc/remoteproc_virtio.c:103
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81de9a40-ffffffff81de9c4b: rp_find_vq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct virtqueue *rp_find_vq(struct virtio_device *vdev, unsigned int id, void (*callback)(struct virtqueue *), const char *name, bool ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81e9fc80)
Location: drivers/remoteproc/remoteproc_virtio.c:103
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
```
**Symbols:**

```
ffffffff81e9fc80-ffffffff81e9fe8b: rp_find_vq (STB_LOCAL)
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
In drivers/remoteproc/remoteproc_virtio.c (ffff800010b831ec)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
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
In drivers/remoteproc/remoteproc_virtio.c (c0c66514)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
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
In drivers/remoteproc/remoteproc_virtio.c (c000000000c605c8)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81898298)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
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
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819089f8)
Location: drivers/remoteproc/remoteproc_virtio.c:65
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_find_vqs
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
