# Function: <code>io_sqe_buffers_register</code>

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
int io_sqe_buffers_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813984e0)
Location: fs/io_uring.c:8427
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc
```
**Symbols:**

```
ffffffff813984e0-ffffffff81398739: io_sqe_buffers_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_sqe_buffers_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e4a20)
Location: fs/io_uring.c:9141
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_register_rsrc
```
**Symbols:**

```
ffffffff813e4a20-ffffffff813e4ced: io_sqe_buffers_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int io_sqe_buffers_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:10465
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/io_uring.c:io_register_rsrc
```
**Symbols:**

```
ffffffff816ceb90-ffffffff816cecf9: io_sqe_buffers_register (STB_LOCAL)
ffffffff81e90e6d-ffffffff81e90fa8: io_sqe_buffers_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_sqe_buffers_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a2a70)
Location: io_uring/rsrc.c:1268
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/rsrc.c:io_register_rsrc
```
**Symbols:**

```
ffffffff817a2a70-ffffffff817a2dd8: io_sqe_buffers_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_sqe_buffers_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e3aa0)
Location: io_uring/rsrc.c:1163
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uring_register
  - io_uring/rsrc.c:io_register_rsrc
```
**Symbols:**

```
ffffffff817e3aa0-ffffffff817e3d7e: io_sqe_buffers_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_sqe_buffers_register(struct io_ring_ctx *ctx, void *arg, unsigned int nr_args, u64 *tags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81827b50)
Location: io_uring/rsrc.c:1005
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_register_rsrc
  - io_uring/register.c:__io_uring_register
```
**Symbols:**

```
ffffffff81827b50-ffffffff81827e2e: io_sqe_buffers_register (STB_GLOBAL)
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
