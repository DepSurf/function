# Function: <code>io_req_normal_work_add</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_req_normal_work_add(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cbc60)
Location: io_uring/io_uring.c:1359
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
**Symbols:**

```
ffffffff817cbc60-ffffffff817cbceb: io_req_normal_work_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_req_normal_work_add(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81810150)
Location: io_uring/io_uring.c:1380
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
**Symbols:**

```
ffffffff81810150-ffffffff818101d8: io_req_normal_work_add (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
