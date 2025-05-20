# Function: <code>io_commit_cqring</code>

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
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e070)
Location: fs/io_uring.c:467
Inline: False
Direct callers:
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff8132e070-ffffffff8132e159: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813414e0)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff813414e0-ffffffff8134168c: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81381df0)
Location: fs/io_uring.c:1184
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_timeout_remove
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_complete_rw_common
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:__io_fail_links
  - fs/io_uring.c:__io_fail_links
  - fs/io_uring.c:io_req_link_next
  - fs/io_uring.c:io_cqring_overflow_flush
  - fs/io_uring.c:io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff81381df0-ffffffff81381f26: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390af0)
Location: fs/io_uring.c:1682
Inline: False
Direct callers:
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_timeout_remove
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_kill_linked_timeout
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff81390af0-ffffffff81390bf8: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81393a50)
Location: fs/io_uring.c:1368
Inline: False
Direct callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_complete
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:__io_req_find_next
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff81393a50-ffffffff81393c48: io_commit_cqring (STB_LOCAL)
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
In fs/io_uring.c (ffffffff813e5e1f)
Location: fs/io_uring.c:1586
Inline: True
Inline callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:__io_req_find_next
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_cqring_overflow_flush
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
In io_uring/io_uring.c (ffffffff81e909a6)
Location: io_uring/io_uring.c:1949
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_kill_timeouts
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_cqring_overflow_flush
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178ee89)
Location: io_uring/io_uring.h:220
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
```
```
In io_uring/rw.c (ffffffff817a4d6b)
Location: io_uring/io_uring.h:220
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d01a9)
Location: io_uring/io_uring.h:227
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_aux_cqe
  - io_uring/io_uring.c:io_cq_unlock_post
```
```
In io_uring/rw.c (ffffffff817e5d39)
Location: io_uring/io_uring.h:227
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8181336c)
Location: io_uring/io_uring.h:228
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_fill_cqe_req_aux
  - io_uring/io_uring.c:io_cq_unlock_post
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
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000104015a0)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffff8000104015a0-ffff800010401760: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d3534)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_complete
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
c05d3534-c05d36f0: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050b1b0)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
c00000000050b1b0-c00000000050b3d4: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ad860)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffe0002ad860-ffffffe0002ad9d6: io_commit_cqring (STB_LOCAL)
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
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81339ac0)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81339ac0-ffffffff81339c6c: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132a7f0)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff8132a7f0-ffffffff8132a99c: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81337590)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81337590-ffffffff8133773c: io_commit_cqring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_commit_cqring(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134a910)
Location: fs/io_uring.c:530
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff8134a910-ffffffff8134aabc: io_commit_cqring (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
