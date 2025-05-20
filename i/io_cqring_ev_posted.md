# Function: <code>io_cqring_ev_posted</code>

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
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d230)
Location: fs/io_uring.c:519
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff8132d230-ffffffff8132d2ac: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81340090)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81340090-ffffffff8134010c: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137c580)
Location: fs/io_uring.c:1222
Inline: False
Direct callers:
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
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
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_async_find_and_cancel
  - fs/io_uring.c:io_timeout_remove
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_add
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
  - fs/io_uring.c:io_req_link_next
  - fs/io_uring.c:io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff8137c580-ffffffff8137c633: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138b8f0)
Location: fs/io_uring.c:1732
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
  - fs/io_uring.c:io_poll_remove_all
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_kill_linked_timeout
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff8138b8f0-ffffffff8138b9ef: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81394d10)
Location: fs/io_uring.c:1417
Inline: False
Direct callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_remove_all
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:__io_req_find_next
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff81394d10-ffffffff81394e20: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e30d0)
Location: fs/io_uring.c:1639
Inline: False
Direct callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_poll_remove_all
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_submit_flush_completions
  - fs/io_uring.c:__io_req_find_next
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_cqring_overflow_flush
```
**Symbols:**

```
ffffffff813e30d0-ffffffff813e31bd: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cc1a7)
Location: io_uring/io_uring.c:2076
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_rsrc_put_work
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_poll_check_events
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:__io_submit_flush_completions
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_cqring_overflow_flush
Direct callers:
  - io_uring/io_uring.c:io_kill_timeouts
  - io_uring/io_uring.c:io_wq_free_work
```
**Symbols:**

```
ffffffff816caa30-ffffffff816caa87: io_cqring_ev_posted (STB_LOCAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010400110)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffff800010400110-ffff80001040018c: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d1f7c)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
c05d1f7c-c05d1ff8: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509630)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
c000000000509630-c0000000005096d0: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ac7e8)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffe0002ac7e8-ffffffe0002ac852: io_cqring_ev_posted (STB_LOCAL)
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
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338670)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81338670-ffffffff813386ec: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813293a0)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff813293a0-ffffffff8132941c: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81336140)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81336140-ffffffff813361bc: io_cqring_ev_posted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_cqring_ev_posted(struct io_ring_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81349210)
Location: fs/io_uring.c:589
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_cqring_add_event
```
**Symbols:**

```
ffffffff81349210-ffffffff8134928c: io_cqring_ev_posted (STB_LOCAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
