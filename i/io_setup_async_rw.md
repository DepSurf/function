# Function: <code>io_setup_async_rw</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int io_setup_async_rw(struct io_kiocb *req, ssize_t io_size, struct iovec *iovec, struct iovec *fast_iov, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137c410)
Location: fs/io_uring.c:2615
Inline: True
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff8137c410-ffffffff8137c49f: io_setup_async_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81397dad)
Location: fs/io_uring.c:3355
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_resubmit_prep
  - fs/io_uring.c:io_resubmit_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139d805)
Location: fs/io_uring.c:3148
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int io_setup_async_rw(struct io_kiocb *req, const struct iovec *iovec, const struct iovec *fast_iov, struct iov_iter *iter, bool force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813de7c0)
Location: fs/io_uring.c:3370
Inline: True
Direct callers:
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
```
**Symbols:**

```
ffffffff813de7c0-ffffffff813de9da: io_setup_async_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_setup_async_rw(struct io_kiocb *req, const struct iovec *iovec, struct io_rw_state *s, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d7320)
Location: io_uring/io_uring.c:3916
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
```
**Symbols:**

```
ffffffff816d7320-ffffffff816d73f5: io_setup_async_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_setup_async_rw(struct io_kiocb *req, const struct iovec *iovec, struct io_rw_state *s, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a3690)
Location: io_uring/rw.c:516
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
```
**Symbols:**

```
ffffffff817a3690-ffffffff817a372f: io_setup_async_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_setup_async_rw(struct io_kiocb *req, const struct iovec *iovec, struct io_rw_state *s, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817e46c0)
Location: io_uring/rw.c:518
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
```
**Symbols:**

```
ffffffff817e46c0-ffffffff817e4758: io_setup_async_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_setup_async_rw(struct io_kiocb *req, const struct iovec *iovec, struct io_rw_state *s, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff81828780)
Location: io_uring/rw.c:569
Inline: False
Direct callers:
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
```
**Symbols:**

```
ffffffff81828780-ffffffff81828830: io_setup_async_rw (STB_LOCAL)
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
<b>Param added. </b>
<code>struct io_rw_state *s</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct iovec *fast_iov</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iov_iter *iter</code>
</li>
<li>
<b>Param reordered. </b>
<code>req, iovec, fast_iov, iter, force</code> ➡️ <code>req, iovec, s, force</code>
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
