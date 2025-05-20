# Function: <code>io_req_task_work_add</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137d94a)
Location: fs/io_uring.c:4137
Inline: True
Inline callers:
  - fs/io_uring.c:__io_async_wake
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_req_task_work_add(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389640)
Location: fs/io_uring.c:2149
Inline: False
Direct callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
```
**Symbols:**

```
ffffffff81389640-ffffffff813896a2: io_req_task_work_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_req_task_work_add(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391e10)
Location: fs/io_uring.c:1952
Inline: False
Direct callers:
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff81391e10-ffffffff81391f8e: io_req_task_work_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void io_req_task_work_add(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:2221
Inline: False
Direct callers:
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_complete_rw
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_free_req_work
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_disarm_next
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_req_complete_post
  - fs/io_uring.c:__io_commit_cqring_flush
  - fs/io_uring.c:__io_commit_cqring_flush
```
**Symbols:**

```
ffffffff813dedb0-ffffffff813def25: io_req_task_work_add (STB_LOCAL)
ffffffff81cc58a3-ffffffff81cc58c0: io_req_task_work_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_req_task_work_add(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d2d8f)
Location: io_uring/io_uring.c:2804
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_link_timeout_fn
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_try_cancel
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_fn
  - io_uring/io_uring.c:io_uring_cmd_complete_in_task
  - io_uring/io_uring.c:io_async_buf_func
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_disarm_next
  - io_uring/io_uring.c:io_disarm_next
  - io_uring/io_uring.c:__io_req_complete_put
Direct callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
**Symbols:**

```
ffffffff816ca520-ffffffff816ca54b: io_req_task_work_add (STB_LOCAL)
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
In io_uring/io_uring.c (ffffffff8178f41a)
Location: io_uring/io_uring.h:96
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_queue_next
  - io_uring/io_uring.c:__io_req_complete_post
  - io_uring/io_uring.c:__io_commit_cqring_flush
```
```
In io_uring/uring_cmd.c (ffffffff81794d0a)
Location: io_uring/io_uring.h:96
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_complete_in_task
```
```
In io_uring/net.c (ffffffff81797e34)
Location: io_uring/io_uring.h:96
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/msg_ring.c (ffffffff81798903)
Location: io_uring/io_uring.h:96
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff81799fb4)
Location: io_uring/io_uring.h:96
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/poll.c (ffffffff8179ca54)
Location: io_uring/io_uring.h:96
Inline: True
Inline callers:
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff817a3d57)
Location: io_uring/io_uring.h:96
Inline: True
Inline callers:
  - io_uring/rw.c:kiocb_done
```
```
In io_uring/notif.c (ffffffff817a51e8)
Location: io_uring/io_uring.h:96
Inline: True
Inline callers:
  - io_uring/notif.c:io_tx_ubuf_callback_ext
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
In io_uring/io_uring.c (ffffffff817d0766)
Location: io_uring/io_uring.h:105
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
```
```
In io_uring/msg_ring.c (ffffffff817d982d)
Location: io_uring/io_uring.h:105
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff817d9e29)
Location: io_uring/io_uring.h:105
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/poll.c (ffffffff817ddc84)
Location: io_uring/io_uring.h:105
Inline: True
Inline callers:
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/rw.c (ffffffff817e4db7)
Location: io_uring/io_uring.h:105
Inline: True
Inline callers:
  - io_uring/rw.c:kiocb_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81813f89)
Location: io_uring/io_uring.h:123
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
```
```
In io_uring/msg_ring.c (ffffffff8181db4d)
Location: io_uring/io_uring.h:123
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff8181e039)
Location: io_uring/io_uring.h:123
Inline: True
Inline callers:
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/rw.c (ffffffff818292cc)
Location: io_uring/io_uring.h:123
Inline: True
Inline callers:
  - io_uring/rw.c:kiocb_done
```
```
In io_uring/waitid.c (ffffffff8182ae8f)
Location: io_uring/io_uring.h:123
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_wait
  - io_uring/waitid.c:io_waitid_cb
```
```
In io_uring/futex.c (ffffffff8182edb5)
Location: io_uring/io_uring.h:123
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wake_fn
  - io_uring/futex.c:io_futex_wakev_fn
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
