# Function: <code>io_buffer_unmap</code>

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
void io_buffer_unmap(struct io_ring_ctx *ctx, struct io_mapped_ubuf **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390ca0)
Location: fs/io_uring.c:8158
Inline: False
Direct callers:
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:__io_sqe_buffers_unregister
  - fs/io_uring.c:io_rsrc_buf_put
```
**Symbols:**

```
ffffffff81390ca0-ffffffff81390d2e: io_buffer_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_buffer_unmap(struct io_ring_ctx *ctx, struct io_mapped_ubuf **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813de1c0)
Location: fs/io_uring.c:8870
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:__io_sqe_buffers_update
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_rsrc_buf_put
```
**Symbols:**

```
ffffffff813de1c0-ffffffff813de24e: io_buffer_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_buffer_unmap(struct io_ring_ctx *ctx, struct io_mapped_ubuf **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c7c00)
Location: io_uring/io_uring.c:10164
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_sqe_buffers_update
  - io_uring/io_uring.c:__io_sqe_buffers_unregister
  - io_uring/io_uring.c:io_rsrc_buf_put
```
**Symbols:**

```
ffffffff816c7c00-ffffffff816c7c9a: io_buffer_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_buffer_unmap(struct io_ring_ctx *ctx, struct io_mapped_ubuf **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a0040)
Location: io_uring/rsrc.c:139
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:io_rsrc_buf_put
  - io_uring/rsrc.c:__io_sqe_buffers_update
```
**Symbols:**

```
ffffffff817a0040-ffffffff817a00da: io_buffer_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_buffer_unmap(struct io_ring_ctx *ctx, struct io_mapped_ubuf **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e1140)
Location: io_uring/rsrc.c:130
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
```
**Symbols:**

```
ffffffff817e1140-ffffffff817e11da: io_buffer_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_buffer_unmap(struct io_ring_ctx *ctx, struct io_mapped_ubuf **slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81825a60)
Location: io_uring/rsrc.c:135
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_buffers_unregister
  - io_uring/rsrc.c:__io_sqe_buffers_update
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
```
**Symbols:**

```
ffffffff81825a60-ffffffff81825afa: io_buffer_unmap (STB_LOCAL)
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
