# Function: <code>io_file_get_normal</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *io_file_get_normal(struct io_ring_ctx *ctx, struct io_kiocb *req, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e0780)
Location: fs/io_uring.c:6927
Inline: False
Direct callers:
  - fs/io_uring.c:io_init_req
  - fs/io_uring.c:__io_splice_prep
```
**Symbols:**

```
ffffffff813e0780-ffffffff813e0815: io_file_get_normal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *io_file_get_normal(struct io_kiocb *req, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cb6b0)
Location: io_uring/io_uring.c:8168
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
```
**Symbols:**

```
ffffffff816cb6b0-ffffffff816cb769: io_file_get_normal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *io_file_get_normal(struct io_kiocb *req, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817909c0)
Location: io_uring/io_uring.c:1983
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_req_prep_async
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
  - io_uring/cancel.c:io_async_cancel
```
**Symbols:**

```
ffffffff817909c0-ffffffff81790a6c: io_file_get_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *io_file_get_normal(struct io_kiocb *req, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d1c00)
Location: io_uring/io_uring.c:2008
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_req_prep_async
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
  - io_uring/cancel.c:io_async_cancel
```
**Symbols:**

```
ffffffff817d1c00-ffffffff817d1caf: io_file_get_normal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *io_file_get_normal(struct io_kiocb *req, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81814f20)
Location: io_uring/io_uring.c:2038
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_req_prep_async
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
  - io_uring/cancel.c:io_async_cancel
```
**Symbols:**

```
ffffffff81814f20-ffffffff81814fcf: io_file_get_normal (STB_GLOBAL)
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
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_ring_ctx *ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, req, fd</code> ➡️ <code>req, fd</code>
</li>
</ul>
</details>
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
