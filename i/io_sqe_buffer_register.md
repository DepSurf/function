# Function: <code>io_sqe_buffer_register</code>

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
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813316b0)
Location: fs/io_uring.c:2887
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff813316b0-ffffffff81331ca7: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813452f0)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff813452f0-ffffffff8134586e: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137f320)
Location: fs/io_uring.c:7267
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8137f320-ffffffff8137f8df: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138d7d0)
Location: fs/io_uring.c:8503
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8138d7d0-ffffffff8138dd24: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, struct iovec *iov, struct io_mapped_ubuf **pimu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813918b0)
Location: fs/io_uring.c:8299
Inline: False
Direct callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff813918b0-ffffffff81391bea: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, struct iovec *iov, struct io_mapped_ubuf **pimu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813df7b0)
Location: fs/io_uring.c:9011
Inline: False
Direct callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff813df7b0-ffffffff813dfb23: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, struct iovec *iov, struct io_mapped_ubuf **pimu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cd530)
Location: io_uring/io_uring.c:10374
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_sqe_buffers_update
  - io_uring/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff816cd530-ffffffff816cd715: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, struct iovec *iov, struct io_mapped_ubuf **pimu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a23d0)
Location: io_uring/rsrc.c:1204
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
**Symbols:**

```
ffffffff817a23d0-ffffffff817a25c9: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, struct iovec *iov, struct io_mapped_ubuf **pimu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e3430)
Location: io_uring/rsrc.c:1069
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
**Symbols:**

```
ffffffff817e3430-ffffffff817e3730: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, struct iovec *iov, struct io_mapped_ubuf **pimu, struct page **last_hpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff818274f0)
Location: io_uring/rsrc.c:911
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
**Symbols:**

```
ffffffff818274f0-ffffffff818277d7: io_sqe_buffer_register (STB_LOCAL)
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
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000104034f8)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
```
**Symbols:**

```
ffff8000104034f8-ffff8000104039c0: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d6be0)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
**Symbols:**

```
c05d6be0-c05d7190: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c0000000005100a0)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
**Symbols:**

```
c0000000005100a0-c0000000005106f4: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ade40)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__se_sys_io_uring_register
```
**Symbols:**

```
ffffffe0002ade40-ffffffe0002ae216: io_sqe_buffer_register (STB_LOCAL)
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
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133d8d0)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8133d8d0-ffffffff8133de4e: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e590)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8132e590-ffffffff8132eb0e: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133b3a0)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8133b3a0-ffffffff8133b91e: io_sqe_buffer_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_sqe_buffer_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134e550)
Location: fs/io_uring.c:3442
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
```
**Symbols:**

```
ffffffff8134e550-ffffffff8134eace: io_sqe_buffer_register (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iovec *iov</code>
</li>
<li>
<b>Param added. </b>
<code>struct io_mapped_ubuf **pimu</code>
</li>
<li>
<b>Param added. </b>
<code>struct page **last_hpage</code>
</li>
<li>
<b>Param removed. </b>
<code>void *arg</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int nr_args</code>
</li>
</ul>
</details>
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
