# Function: <code>io_req_defer</code>

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
In fs/io_uring.c (ffffffff8132faf9)
Location: fs/io_uring.c:1746
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813423c0)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff813423c0-ffffffff8134258f: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_req_defer(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81386950)
Location: fs/io_uring.c:5201
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff81386950-ffffffff81386b03: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_req_defer(struct io_kiocb *req, const struct io_uring_sqe *sqe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81395c40)
Location: fs/io_uring.c:6142
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff81395c40-ffffffff81395efb: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_req_defer(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139e050)
Location: fs/io_uring.c:6028
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff8139e050-ffffffff8139e263: io_req_defer (STB_LOCAL)
```
</details>
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
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000104024b8)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffff8000104024b8-ffff8000104026b0: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d2fa0)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
c05d2fa0-c05d315c: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050c580)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
c00000000050c580-c00000000050c824: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ae73a)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffe0002ae73a-ffffffe0002ae8f2: io_req_defer (STB_LOCAL)
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
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133a9a0)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff8133a9a0-ffffffff8133ab6f: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132b6a0)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff8132b6a0-ffffffff8132b85f: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338470)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff81338470-ffffffff8133863f: io_req_defer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_req_defer(struct io_ring_ctx *ctx, struct io_kiocb *req, struct sqe_submit *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134a410)
Location: fs/io_uring.c:2051
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
```
**Symbols:**

```
ffffffff8134a410-ffffffff8134a5c9: io_req_defer (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct io_uring_sqe *sqe</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sqe_submit *s</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, req, s</code> ➡️ <code>req, sqe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct io_uring_sqe *sqe</code>
</li>
</ul>
</details>
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
