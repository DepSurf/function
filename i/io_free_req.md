# Function: <code>io_free_req</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e210)
Location: fs/io_uring.c:658
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
ffffffff8132e210-ffffffff8132e364: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81341700)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
ffffffff81341700-ffffffff81341882: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81385f7b)
Location: fs/io_uring.c:1625
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req
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
In fs/io_uring.c (ffffffff81391184)
Location: fs/io_uring.c:2258
Inline: True
Inline callers:
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
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
In fs/io_uring.c (ffffffff813a03f0)
Location: fs/io_uring.c:2101
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_complete_failed
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
In fs/io_uring.c (ffffffff813e9481)
Location: fs/io_uring.c:2318
Inline: True
Inline callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_free_req_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e90fa8)
Location: io_uring/io_uring.c:2513
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_wq_free_work
```
**Symbols:**

```
ffffffff81e90fa8-ffffffff81e91067: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178dc80)
Location: io_uring/io_uring.c:1073
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
**Symbols:**

```
ffffffff8178dc80-ffffffff8178dd97: io_free_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d1a42)
Location: io_uring/io_uring.c:1123
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_free_work
Direct callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
**Symbols:**

```
ffffffff817cfd60-ffffffff817cfdb1: io_free_req (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81814d62)
Location: io_uring/io_uring.c:1127
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_free_work
Direct callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
```
**Symbols:**

```
ffffffff81812ef0-ffffffff81812f41: io_free_req (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010401830)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
ffff800010401830-ffff8000104019fc: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d37a8)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
c05d37a8-c05d3948: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050b470)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
c00000000050b470-c00000000050b6e8: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ada48)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_send_recvmsg
  - fs/io_uring.c:io_complete_rw
  - fs/io_uring.c:io_iopoll_getevents
```
**Symbols:**

```
ffffffe0002ada48-ffffffe0002adb8e: io_free_req (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81339ce0)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
ffffffff81339ce0-ffffffff81339e62: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132aa10)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
ffffffff8132aa10-ffffffff8132ab92: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813377b0)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
ffffffff813377b0-ffffffff81337932: io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134ab30)
Location: fs/io_uring.c:721
Inline: False
Direct callers:
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
**Symbols:**

```
ffffffff8134ab30-ffffffff8134acb2: io_free_req (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
