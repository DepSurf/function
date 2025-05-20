# Function: <code>io_req_map_rw</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_req_map_rw(struct io_kiocb *req, ssize_t io_size, struct iovec *iovec, struct iovec *fast_iov, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137ad30)
Location: fs/io_uring.c:2584
Inline: False
```
**Symbols:**

```
ffffffff8137ad30-ffffffff8137ad9e: io_req_map_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_req_map_rw(struct io_kiocb *req, const struct iovec *iovec, const struct iovec *fast_iov, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389000)
Location: fs/io_uring.c:3313
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_resubmit_prep
```
**Symbols:**

```
ffffffff81389000-ffffffff813890c1: io_req_map_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_req_map_rw(struct io_kiocb *req, const struct iovec *iovec, const struct iovec *fast_iov, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390110)
Location: fs/io_uring.c:3114
Inline: False
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff81390110-ffffffff813901ce: io_req_map_rw (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813de869)
Location: fs/io_uring.c:3336
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_req_map_rw(struct io_kiocb *req, const struct iovec *iovec, const struct iovec *fast_iov, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c6f40)
Location: io_uring/io_uring.c:3878
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_setup_async_rw
```
**Symbols:**

```
ffffffff816c6f40-ffffffff816c701b: io_req_map_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_req_map_rw(struct io_kiocb *req, const struct iovec *iovec, const struct iovec *fast_iov, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a35a0)
Location: io_uring/rw.c:489
Inline: False
Direct callers:
  - io_uring/rw.c:io_setup_async_rw
```
**Symbols:**

```
ffffffff817a35a0-ffffffff817a367b: io_req_map_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void io_req_map_rw(struct io_kiocb *req, const struct iovec *iovec, const struct iovec *fast_iov, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rw.c (0)
Location: io_uring/rw.c:491
Inline: False
Direct callers:
  - io_uring/rw.c:io_setup_async_rw
```
**Symbols:**

```
ffffffff817e4540-ffffffff817e46b0: io_req_map_rw (STB_LOCAL)
ffffffff820f7aba-ffffffff820f7adf: io_req_map_rw.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void io_req_map_rw(struct io_kiocb *req, const struct iovec *iovec, const struct iovec *fast_iov, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/rw.c (0)
Location: io_uring/rw.c:542
Inline: False
Direct callers:
  - io_uring/rw.c:io_setup_async_rw
```
**Symbols:**

```
ffffffff81828610-ffffffff8182876f: io_req_map_rw (STB_LOCAL)
ffffffff821d5459-ffffffff821d547e: io_req_map_rw.cold (STB_LOCAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ssize_t io_size</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, io_size, iovec, fast_iov, iter</code> ➡️ <code>req, iovec, fast_iov, iter</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct iovec *iovec</code> ➡️ <code>const struct iovec *iovec</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct iovec *fast_iov</code> ➡️ <code>const struct iovec *fast_iov</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
