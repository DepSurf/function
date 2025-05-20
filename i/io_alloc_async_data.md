# Function: <code>io_alloc_async_data</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81399408)
Location: fs/io_uring.c:3347
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_req_defer
  - fs/io_uring.c:io_timeout_prep
  - fs/io_uring.c:io_connect
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
In fs/io_uring.c (ffffffff8139c241)
Location: fs/io_uring.c:3141
Inline: True
Inline callers:
  - fs/io_uring.c:io_timeout_prep
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_write
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
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
In fs/io_uring.c (ffffffff813e613c)
Location: fs/io_uring.c:3363
Inline: True
Inline callers:
  - fs/io_uring.c:io_timeout_prep
  - fs/io_uring.c:io_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d55f7)
Location: io_uring/io_uring.c:3905
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_timeout_prep
  - io_uring/io_uring.c:io_connect
  - io_uring/io_uring.c:io_setup_async_msg
  - io_uring/io_uring.c:io_uring_cmd
  - io_uring/io_uring.c:io_setup_async_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool io_alloc_async_data(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81790780)
Location: io_uring/io_uring.c:1715
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_req_prep_async
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/rw.c:io_setup_async_rw
```
**Symbols:**

```
ffffffff81790780-ffffffff817907e3: io_alloc_async_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool io_alloc_async_data(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d19a0)
Location: io_uring/io_uring.c:1758
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_req_prep_async
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/rw.c:io_setup_async_rw
```
**Symbols:**

```
ffffffff817d19a0-ffffffff817d19fa: io_alloc_async_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_alloc_async_data(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81814cc0)
Location: io_uring/io_uring.c:1782
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_req_prep_async
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/rw.c:io_setup_async_rw
  - io_uring/waitid.c:io_waitid
```
**Symbols:**

```
ffffffff81814cc0-ffffffff81814d1a: io_alloc_async_data (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
