# Function: <code>io_rsrc_data_alloc</code>

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
struct io_rsrc_data *io_rsrc_data_alloc(struct io_ring_ctx *ctx, rsrc_put_fn *do_put, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813920c0)
Location: fs/io_uring.c:7195
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff813920c0-ffffffff81392167: io_rsrc_data_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_rsrc_data_alloc(struct io_ring_ctx *ctx, rsrc_put_fn *do_put, u64 *utags, unsigned int nr, struct io_rsrc_data **pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e0d40)
Location: fs/io_uring.c:7866
Inline: False
Direct callers:
  - fs/io_uring.c:io_sqe_buffers_register
  - fs/io_uring.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff813e0d40-ffffffff813e0f0a: io_rsrc_data_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_rsrc_data_alloc(struct io_ring_ctx *ctx, rsrc_put_fn *do_put, u64 *utags, unsigned int nr, struct io_rsrc_data **pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e85c)
Location: io_uring/io_uring.c:9179
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_sqe_buffers_register
  - io_uring/io_uring.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff81e8e85c-ffffffff81e8ea12: io_rsrc_data_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_rsrc_data_alloc(struct io_ring_ctx *ctx, rsrc_put_fn *do_put, u64 *utags, unsigned int nr, struct io_rsrc_data **pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817a0590)
Location: io_uring/rsrc.c:408
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff817a0590-ffffffff817a078a: io_rsrc_data_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_rsrc_data_alloc(struct io_ring_ctx *ctx, int type, u64 *utags, unsigned int nr, struct io_rsrc_data **pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff817e18c0)
Location: io_uring/rsrc.c:312
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff817e18c0-ffffffff817e1a7f: io_rsrc_data_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_rsrc_data_alloc(struct io_ring_ctx *ctx, int type, u64 *utags, unsigned int nr, struct io_rsrc_data **pdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rsrc.c (ffffffff81825c50)
Location: io_uring/rsrc.c:317
Inline: False
Direct callers:
  - io_uring/rsrc.c:io_sqe_buffers_register
  - io_uring/rsrc.c:io_sqe_files_register
```
**Symbols:**

```
ffffffff81825c50-ffffffff81825e3e: io_rsrc_data_alloc (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 *utags</code>
</li>
<li>
<b>Param added. </b>
<code>struct io_rsrc_data **pdata</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, do_put, nr</code> ➡️ <code>ctx, do_put, utags, nr, pdata</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct io_rsrc_data *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int type</code>
</li>
<li>
<b>Param removed. </b>
<code>rsrc_put_fn *do_put</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
