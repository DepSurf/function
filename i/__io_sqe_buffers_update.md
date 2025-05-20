# Function: <code>__io_sqe_buffers_update</code>

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
int __io_sqe_buffers_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813981a0)
Location: fs/io_uring.c:8486
Inline: False
Direct callers:
  - fs/io_uring.c:io_register_rsrc_update
```
**Symbols:**

```
ffffffff813981a0-ffffffff813984df: __io_sqe_buffers_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __io_sqe_buffers_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e3cf0)
Location: fs/io_uring.c:9193
Inline: False
Direct callers:
  - fs/io_uring.c:io_register_rsrc_update
```
**Symbols:**

```
ffffffff813e3cf0-ffffffff813e3fac: __io_sqe_buffers_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __io_sqe_buffers_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cd720)
Location: io_uring/io_uring.c:10522
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_register_rsrc_update
```
**Symbols:**

```
ffffffff816cd720-ffffffff816cd9f6: __io_sqe_buffers_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_sqe_buffers_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a25e0)
Location: io_uring/rsrc.c:528
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_register_rsrc_update
```
**Symbols:**

```
ffffffff817a25e0-ffffffff817a28ad: __io_sqe_buffers_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __io_sqe_buffers_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e3740)
Location: io_uring/rsrc.c:424
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_register_rsrc_update
```
**Symbols:**

```
ffffffff817e3740-ffffffff817e399e: __io_sqe_buffers_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __io_sqe_buffers_update(struct io_ring_ctx *ctx, struct io_uring_rsrc_update2 *up, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff818277f0)
Location: io_uring/rsrc.c:419
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_register_rsrc_update
```
**Symbols:**

```
ffffffff818277f0-ffffffff81827a4b: __io_sqe_buffers_update (STB_LOCAL)
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
