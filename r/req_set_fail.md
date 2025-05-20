# Function: <code>req_set_fail</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e9abe)
Location: fs/io_uring.c:1261
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_req_task_timeout
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_close
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_complete_rw
  - fs/io_uring.c:io_req_task_cancel
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
In io_uring/io_uring.c (ffffffff81e919b7)
Location: io_uring/io_uring.c:1620
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_timeout_fn
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_add
  - io_uring/io_uring.c:io_poll_task_func
  - io_uring/io_uring.c:io_connect
  - io_uring/io_uring.c:io_socket
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_send
  - io_uring/io_uring.c:io_sendmsg
  - io_uring/io_uring.c:io_shutdown
  - io_uring/io_uring.c:io_sync_file_range
  - io_uring/io_uring.c:io_close
  - io_uring/io_uring.c:io_statx
  - io_uring/io_uring.c:io_fadvise
  - io_uring/io_uring.c:io_madvise
  - io_uring/io_uring.c:io_epoll_ctl
  - io_uring/io_uring.c:io_provide_buffers
  - io_uring/io_uring.c:io_remove_buffers
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_fallocate
  - io_uring/io_uring.c:io_fsync
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
  - io_uring/io_uring.c:io_uring_cmd_done
  - io_uring/io_uring.c:io_uring_cmd_done
  - io_uring/io_uring.c:io_linkat
  - io_uring/io_uring.c:io_symlinkat
  - io_uring/io_uring.c:io_mkdirat
  - io_uring/io_uring.c:io_unlinkat
  - io_uring/io_uring.c:io_setxattr
  - io_uring/io_uring.c:io_fsetxattr
  - io_uring/io_uring.c:io_getxattr
  - io_uring/io_uring.c:io_fgetxattr
  - io_uring/io_uring.c:io_renameat
  - io_uring/io_uring.c:__io_complete_rw_common
  - io_uring/io_uring.c:io_req_complete_failed
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
In io_uring/io_uring.c (ffffffff81791166)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/splice.c (ffffffff817939bd)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
```
```
In io_uring/advise.c (ffffffff81793eac)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
```
```
In io_uring/openclose.c (ffffffff81794bff)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/uring_cmd.c (ffffffff81795040)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
```
In io_uring/epoll.c (ffffffff817951e9)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
```
```
In io_uring/net.c (ffffffff817984f0)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
```
```
In io_uring/msg_ring.c (ffffffff81798a41)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff81799f4e)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_fn
```
```
In io_uring/poll.c (ffffffff8179e0c3)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/cancel.c (ffffffff8179e74c)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff8179f9f1)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
```
```
In io_uring/rsrc.c (ffffffff817a1b9a)
Location: io_uring/io_uring.h:172
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (ffffffff817a3b81)
Location: io_uring/io_uring.h:172
Inline: True
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
In io_uring/io_uring.c (ffffffff817d1e46)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/splice.c (ffffffff817d46f0)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
```
```
In io_uring/advise.c (ffffffff817d4bf7)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
```
```
In io_uring/openclose.c (ffffffff817d5862)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/uring_cmd.c (ffffffff817d5d5a)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
```
In io_uring/epoll.c (ffffffff817d5ed9)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
```
```
In io_uring/net.c (ffffffff817d9292)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
```
```
In io_uring/msg_ring.c (ffffffff817d9b0f)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff817dac46)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_fn
```
```
In io_uring/poll.c (ffffffff817df1e9)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/cancel.c (ffffffff817df93c)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff817e0b00)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
```
```
In io_uring/rsrc.c (ffffffff817e2d0d)
Location: io_uring/io_uring.h:179
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (ffffffff817e4be1)
Location: io_uring/io_uring.h:179
Inline: True
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
In io_uring/io_uring.c (ffffffff81815166)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/splice.c (ffffffff81818560)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
```
```
In io_uring/advise.c (ffffffff81818a57)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
```
```
In io_uring/openclose.c (ffffffff8181983e)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/openclose.c:io_install_fixed_fd
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/uring_cmd.c (ffffffff81819fc5)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
```
In io_uring/epoll.c (ffffffff8181a139)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
```
```
In io_uring/net.c (ffffffff8181d5e3)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
```
```
In io_uring/msg_ring.c (ffffffff8181de2f)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff8181ef3e)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_fn
```
```
In io_uring/poll.c (ffffffff818235cd)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/cancel.c (ffffffff81823dd4)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff81824ff6)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
```
```
In io_uring/rsrc.c (ffffffff81826c6d)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (ffffffff81829041)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/rw.c:__io_complete_rw_common
```
```
In io_uring/waitid.c (ffffffff8182ae0e)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_complete
```
```
In io_uring/futex.c (ffffffff8182fa89)
Location: io_uring/io_uring.h:180
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wake
  - io_uring/futex.c:io_futex_wait
  - io_uring/futex.c:io_futexv_wait
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
