# Function: <code>io_req_complete_failed</code>

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
void io_req_complete_failed(struct io_kiocb *req, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81395c50)
Location: fs/io_uring.c:1674
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:__io_req_task_submit
  - fs/io_uring.c:io_req_task_cancel
```
**Symbols:**

```
ffffffff81395c50-ffffffff81395cc5: io_req_complete_failed (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813e9abe)
Location: fs/io_uring.c:1898
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_req_task_cancel
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_req_complete_failed(struct io_kiocb *req, s32 res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d0370)
Location: io_uring/io_uring.c:2402
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_queue_sqe_fallback
  - io_uring/io_uring.c:io_queue_sqe_fallback
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_apoll_task_func
  - io_uring/io_uring.c:io_req_task_cancel
```
**Symbols:**

```
ffffffff816d0370-ffffffff816d0413: io_req_complete_failed (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
