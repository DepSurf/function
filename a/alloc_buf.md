# Function: <code>alloc_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81516e60)
Location: drivers/char/virtio_console.c:420
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:fill_queue
```
**Symbols:**

```
ffffffff81516e60-ffffffff81516fd0: alloc_buf.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81569b10)
Location: drivers/char/virtio_console.c:426
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81569b10-ffffffff81569c80: alloc_buf.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815963a0)
Location: drivers/char/virtio_console.c:425
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff815963a0-ffffffff81596510: alloc_buf.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815aa180)
Location: drivers/char/virtio_console.c:425
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff815aa180-ffffffff815aa2e8: alloc_buf.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81610af0)
Location: drivers/char/virtio_console.c:425
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81610af0-ffffffff81610c5f: alloc_buf.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164a680)
Location: drivers/char/virtio_console.c:425
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8164a680-ffffffff8164a82d: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81668870)
Location: drivers/char/virtio_console.c:425
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81668870-ffffffff81668994: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169f570)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8169f570-ffffffff8169f6a0: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c2300)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff816c2300-ffffffff816c2430: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81774a90)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81774a90-ffffffff81774bc9: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8178f7f0)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff8178f7f0-ffffffff8178f91b: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81772380)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81772380-ffffffff8177248d: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff817f8450)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff817f8450-ffffffff817f855d: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81936d70)
Location: drivers/char/virtio_console.c:413
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_write
```
**Symbols:**

```
ffffffff81936d70-ffffffff81936e9c: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81a96c30)
Location: drivers/char/virtio_console.c:405
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_write
```
**Symbols:**

```
ffffffff81a96c30-ffffffff81a96d5c: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81ae2440)
Location: drivers/char/virtio_console.c:406
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_write
```
**Symbols:**

```
ffffffff81ae2440-ffffffff81ae2561: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81b35830)
Location: drivers/char/virtio_console.c:403
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_write
```
**Symbols:**

```
ffffffff81b35830-ffffffff81b35951: alloc_buf (STB_LOCAL)
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
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b4548)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffff8000108b4548-ffff8000108b4668: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09af1d4)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
c09af1d4-c09af304: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094e5e0)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
c00000000094e5e0-c00000000094e774: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe0005653e4)
Location: drivers/char/virtio_console.c:412
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffe0005653e4-ffffffe0005654c4: alloc_buf.isra.0 (STB_LOCAL)
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
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81687d50)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff81687d50-ffffffff81687e80: alloc_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816658e0)
Location: drivers/char/virtio_console.c:412
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff816658e0-ffffffff816659af: alloc_buf.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b6090)
Location: drivers/char/virtio_console.c:412
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff816b6090-ffffffff816b615f: alloc_buf.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct port_buffer *alloc_buf(struct virtio_device *vdev, size_t buf_size, int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816d0630)
Location: drivers/char/virtio_console.c:412
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
```
**Symbols:**

```
ffffffff816d0630-ffffffff816d0760: alloc_buf (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
