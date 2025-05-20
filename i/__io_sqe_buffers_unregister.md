# Function: <code>__io_sqe_buffers_unregister</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391f90)
Location: fs/io_uring.c:8179
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff81391f90-ffffffff81392019: __io_sqe_buffers_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ee54e)
Location: fs/io_uring.c:8891
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_sqe_buffers_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e720)
Location: io_uring/io_uring.c:10185
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_ring_ctx_free
  - io_uring/io_uring.c:io_sqe_buffers_register
```
**Symbols:**

```
ffffffff81e8e720-ffffffff81e8e790: __io_sqe_buffers_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a2c51)
Location: io_uring/rsrc.c:1038
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff817a2000-ffffffff817a2088: __io_sqe_buffers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e3120)
Location: io_uring/rsrc.c:928
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff817e3120-ffffffff817e31a3: __io_sqe_buffers_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __io_sqe_buffers_unregister(struct io_ring_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff818271d0)
Location: io_uring/rsrc.c:773
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
Direct callers:
  - io_uring/io_uring.c:io_ring_ctx_free
```
**Symbols:**

```
ffffffff818271d0-ffffffff81827253: __io_sqe_buffers_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
