# Function: <code>__io_req_task_work_add</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __io_req_task_work_add(struct io_kiocb *req, struct io_uring_task *tctx, struct io_wq_work_list *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:2764
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_link_timeout_fn
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_fn
  - io_uring/io_uring.c:io_uring_cmd_complete_in_task
  - io_uring/io_uring.c:io_async_buf_func
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_disarm_next
  - io_uring/io_uring.c:io_disarm_next
  - io_uring/io_uring.c:__io_req_complete_put
```
**Symbols:**

```
ffffffff816ca380-ffffffff816ca51c: __io_req_task_work_add (STB_LOCAL)
ffffffff81e8fa82-ffffffff81e8fa9f: __io_req_task_work_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __io_req_task_work_add(struct io_kiocb *req, bool allow_local);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178ddb0)
Location: io_uring/io_uring.c:1268
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - io_uring/uring_cmd.c:io_uring_cmd_complete_in_task
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/poll.c:__io_poll_execute
  - io_uring/rw.c:kiocb_done
  - io_uring/notif.c:io_tx_ubuf_callback_ext
```
**Symbols:**

```
ffffffff8178ddb0-ffffffff8178df79: __io_req_task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __io_req_task_work_add(struct io_kiocb *req, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff817d0766)
Location: io_uring/io_uring.c:1377
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - io_uring/uring_cmd.c:io_uring_cmd_do_in_task_lazy
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/poll.c:__io_poll_execute
  - io_uring/rw.c:kiocb_done
  - io_uring/notif.c:io_tx_ubuf_callback_ext
```
**Symbols:**

```
ffffffff817c9830-ffffffff817c9926: __io_req_task_work_add.part.0 (STB_LOCAL)
ffffffff817cfdd0-ffffffff817cfe06: __io_req_task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __io_req_task_work_add(struct io_kiocb *req, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff81813f89)
Location: io_uring/io_uring.c:1398
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
Direct callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_free_work
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:io_req_complete_post
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
  - io_uring/uring_cmd.c:__io_uring_cmd_do_in_task
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/poll.c:__io_poll_execute
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_complete_rw
  - io_uring/notif.c:io_tx_ubuf_callback_ext
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_wait
  - io_uring/waitid.c:io_waitid_cb
  - io_uring/futex.c:io_futex_wake_fn
  - io_uring/futex.c:io_futex_wakev_fn
```
**Symbols:**

```
ffffffff8180e000-ffffffff8180e120: __io_req_task_work_add.part.0 (STB_LOCAL)
ffffffff81812f60-ffffffff81812f96: __io_req_task_work_add (STB_GLOBAL)
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
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool allow_local</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_uring_task *tctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_wq_work_list *list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool allow_local</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
