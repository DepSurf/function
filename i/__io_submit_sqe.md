# Function: <code>__io_submit_sqe</code>

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
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132f0a0)
Location: fs/io_uring.c:1774
Inline: False
Direct callers:
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
ffffffff8132f0a0-ffffffff8132f726: __io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81342590)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
ffffffff81342590-ffffffff81342e68: __io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010404108)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
ffff800010404108-ffff800010404a20: __io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d3b78)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
c05d3b78-c05d4430: __io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050c830)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
c00000000050c830-c00000000050d310: __io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002aeaa8)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
ffffffe0002aeaa8-ffffffe0002af1d0: __io_submit_sqe (STB_LOCAL)
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
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133ab70)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
ffffffff8133ab70-ffffffff8133b448: __io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132b860)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
ffffffff8132b860-ffffffff8132c126: __io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338640)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
ffffffff81338640-ffffffff81338f18: __io_submit_sqe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __io_submit_sqe(struct io_ring_ctx *ctx, struct io_kiocb *req, const struct sqe_submit *s, bool force_nonblock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134aed0)
Location: fs/io_uring.c:2080
Inline: False
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
```
**Symbols:**

```
ffffffff8134aed0-ffffffff8134b777: __io_submit_sqe (STB_LOCAL)
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
