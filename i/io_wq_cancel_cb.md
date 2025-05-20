# Function: <code>io_wq_cancel_cb</code>

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
enum io_wq_cancel io_wq_cancel_cb(struct io_wq *wq, work_cancel_fn *cancel, void *data, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8138b1a0)
Location: fs/io-wq.c:984
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_flush
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io-wq.c:io_wq_cancel_work
```
**Symbols:**

```
ffffffff8138b1a0-ffffffff8138b319: io_wq_cancel_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq *wq, work_cancel_fn *cancel, void *data, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff8139c370)
Location: fs/io-wq.c:1004
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_async_find_and_cancel
```
**Symbols:**

```
ffffffff8139c370-ffffffff8139c4ee: io_wq_cancel_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq *wq, work_cancel_fn *cancel, void *data, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io-wq.c (ffffffff813a34c0)
Location: fs/io-wq.c:882
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_async_cancel
```
**Symbols:**

```
ffffffff813a34c0-ffffffff813a3638: io_wq_cancel_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq *wq, work_cancel_fn *cancel, void *data, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io-wq.c (0)
Location: fs/io-wq.c:1060
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_try_cancel_userdata
```
**Symbols:**

```
ffffffff81cc5fe1-ffffffff81cc600b: io_wq_cancel_cb.cold (STB_LOCAL)
ffffffff813f29a0-ffffffff813f2b34: io_wq_cancel_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq *wq, work_cancel_fn *cancel, void *data, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1085
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_async_cancel_one
```
**Symbols:**

```
ffffffff81e92d79-ffffffff81e92da3: io_wq_cancel_cb.cold (STB_LOCAL)
ffffffff816db540-ffffffff816db699: io_wq_cancel_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq *wq, work_cancel_fn *cancel, void *data, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1072
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/cancel.c:io_async_cancel_one
```
**Symbols:**

```
ffffffff82077b26-ffffffff82077b50: io_wq_cancel_cb.cold (STB_LOCAL)
ffffffff817a7630-ffffffff817a777b: io_wq_cancel_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq *wq, work_cancel_fn *cancel, void *data, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1062
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/cancel.c:io_async_cancel_one
```
**Symbols:**

```
ffffffff820f7c02-ffffffff820f7c3e: io_wq_cancel_cb.cold (STB_LOCAL)
ffffffff817e8680-ffffffff817e876a: io_wq_cancel_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum io_wq_cancel io_wq_cancel_cb(struct io_wq *wq, work_cancel_fn *cancel, void *data, bool cancel_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io-wq.c (0)
Location: io_uring/io-wq.c:1083
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/cancel.c:io_async_cancel_one
```
**Symbols:**

```
ffffffff821d55d2-ffffffff821d560e: io_wq_cancel_cb.cold (STB_LOCAL)
ffffffff8182e420-ffffffff8182e50a: io_wq_cancel_cb (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
