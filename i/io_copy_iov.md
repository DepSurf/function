# Function: <code>io_copy_iov</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81331771)
Location: fs/io_uring.c:2862
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (ffffffff813453b1)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (ffffffff8137f3d6)
Location: fs/io_uring.c:7242
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (ffffffff8138d877)
Location: fs/io_uring.c:8410
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int io_copy_iov(struct io_ring_ctx *ctx, struct iovec *dst, void *arg, unsigned int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390e30)
Location: fs/io_uring.c:8205
Inline: True
Direct callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff81390e30-ffffffff81390ec2: io_copy_iov (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int io_copy_iov(struct io_ring_ctx *ctx, struct iovec *dst, void *arg, unsigned int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813de720)
Location: fs/io_uring.c:8917
Inline: True
Direct callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff813de720-ffffffff813de7b2: io_copy_iov (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_copy_iov(struct io_ring_ctx *ctx, struct iovec *dst, void *arg, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c7de0)
Location: io_uring/io_uring.c:10218
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_sqe_buffers_update
  - io_uring/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff816c7de0-ffffffff816c7e83: io_copy_iov (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_copy_iov(struct io_ring_ctx *ctx, struct iovec *dst, void *arg, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff8179ff80)
Location: io_uring/rsrc.c:90
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
**Symbols:**

```
ffffffff8179ff80-ffffffff817a0023: io_copy_iov (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_copy_iov(struct io_ring_ctx *ctx, struct iovec *dst, void *arg, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e11f0)
Location: io_uring/rsrc.c:81
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
**Symbols:**

```
ffffffff817e11f0-ffffffff817e1293: io_copy_iov (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_copy_iov(struct io_ring_ctx *ctx, struct iovec *dst, void *arg, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81825b10)
Location: io_uring/rsrc.c:86
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
**Symbols:**

```
ffffffff81825b10-ffffffff81825bb3: io_copy_iov (STB_LOCAL)
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
In fs/io_uring.c (ffff800010403598)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (c05d6c58)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (c00000000051019c)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (ffffffe0002adecc)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (ffffffff8133d991)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (ffffffff8132e651)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (ffffffff8133b461)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
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
In fs/io_uring.c (ffffffff8134e611)
Location: fs/io_uring.c:3417
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqe_buffer_register
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
