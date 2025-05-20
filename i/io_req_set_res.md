# Function: <code>io_req_set_res</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178f40b)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/xattr.c (ffffffff81792f90)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
```
```
In io_uring/nop.c (ffffffff81793065)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/nop.c:io_nop
```
```
In io_uring/fs.c (ffffffff8179368f)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/fs.c:io_linkat
  - io_uring/fs.c:io_symlinkat
  - io_uring/fs.c:io_mkdirat
  - io_uring/fs.c:io_unlinkat
  - io_uring/fs.c:io_renameat
```
```
In io_uring/splice.c (ffffffff81793960)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
```
```
In io_uring/sync.c (ffffffff81793c81)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
  - io_uring/sync.c:io_fsync
  - io_uring/sync.c:io_sync_file_range
```
```
In io_uring/advise.c (ffffffff81793ec8)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
  - io_uring/advise.c:io_madvise
```
```
In io_uring/openclose.c (ffffffff81794c1a)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/uring_cmd.c (ffffffff8179505c)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
```
In io_uring/epoll.c (ffffffff81795205)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
```
```
In io_uring/statx.c (ffffffff81795317)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/statx.c:io_statx
```
```
In io_uring/net.c (ffffffff8179850f)
Location: io_uring/io_uring.h:181
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
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_shutdown
```
```
In io_uring/msg_ring.c (ffffffff81798a60)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff81799fa9)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_req_tw_fail_links
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/poll.c (ffffffff8179dfec)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:__io_poll_execute
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_check_events
```
```
In io_uring/cancel.c (ffffffff8179e715)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff8179fa26)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
```
```
In io_uring/rsrc.c (ffffffff817a1b51)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (ffffffff817a4c42)
Location: io_uring/io_uring.h:181
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_fail
  - io_uring/rw.c:kiocb_done
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
In io_uring/io_uring.c (ffffffff817d0753)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/xattr.c (ffffffff817d3cf0)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
```
```
In io_uring/nop.c (ffffffff817d3dc5)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/nop.c:io_nop
```
```
In io_uring/fs.c (ffffffff817d43af)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/fs.c:io_linkat
  - io_uring/fs.c:io_symlinkat
  - io_uring/fs.c:io_mkdirat
  - io_uring/fs.c:io_unlinkat
  - io_uring/fs.c:io_renameat
```
```
In io_uring/splice.c (ffffffff817d4693)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
```
```
In io_uring/sync.c (ffffffff817d49a1)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
  - io_uring/sync.c:io_fsync
  - io_uring/sync.c:io_sync_file_range
```
```
In io_uring/advise.c (ffffffff817d4c13)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
  - io_uring/advise.c:io_madvise
```
```
In io_uring/openclose.c (ffffffff817d587e)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/uring_cmd.c (ffffffff817d5d7a)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
```
In io_uring/epoll.c (ffffffff817d5ef5)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
```
```
In io_uring/statx.c (ffffffff817d6007)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/statx.c:io_statx
```
```
In io_uring/net.c (ffffffff817d92ae)
Location: io_uring/io_uring.h:188
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
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_shutdown
```
```
In io_uring/msg_ring.c (ffffffff817d9b2b)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff817daa5e)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_req_tw_fail_links
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/poll.c (ffffffff817df2d2)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:__io_poll_execute
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_check_events
```
```
In io_uring/cancel.c (ffffffff817df905)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff817e0b36)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
```
```
In io_uring/rsrc.c (ffffffff817e2cc4)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (ffffffff817e5c12)
Location: io_uring/io_uring.h:188
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_fail
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
In io_uring/io_uring.c (ffffffff81813f76)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_submit_fail_init
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/xattr.c (ffffffff81817b7d)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
```
```
In io_uring/nop.c (ffffffff81817c45)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/nop.c:io_nop
```
```
In io_uring/fs.c (ffffffff8181821f)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/fs.c:io_linkat
  - io_uring/fs.c:io_symlinkat
  - io_uring/fs.c:io_mkdirat
  - io_uring/fs.c:io_unlinkat
  - io_uring/fs.c:io_renameat
```
```
In io_uring/splice.c (ffffffff81818503)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_tee
```
```
In io_uring/sync.c (ffffffff81818811)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
  - io_uring/sync.c:io_fsync
  - io_uring/sync.c:io_sync_file_range
```
```
In io_uring/advise.c (ffffffff81818a73)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
  - io_uring/advise.c:io_madvise
```
```
In io_uring/openclose.c (ffffffff8181985a)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/openclose.c:io_install_fixed_fd
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_openat2
```
```
In io_uring/uring_cmd.c (ffffffff81819fe3)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
```
In io_uring/epoll.c (ffffffff8181a155)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
```
```
In io_uring/statx.c (ffffffff8181a267)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/statx.c:io_statx
```
```
In io_uring/net.c (ffffffff8181d5ff)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_shutdown
```
```
In io_uring/msg_ring.c (ffffffff8181de4b)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_tw_fd_complete
  - io_uring/msg_ring.c:io_msg_tw_complete
```
```
In io_uring/timeout.c (ffffffff8181ed52)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_req_tw_fail_links
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/poll.c (ffffffff818236b6)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:io_poll_task_func
  - io_uring/poll.c:io_poll_check_events
  - io_uring/poll.c:__io_poll_execute
```
```
In io_uring/cancel.c (ffffffff81823d9d)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff81825013)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
```
```
In io_uring/rsrc.c (ffffffff81826c24)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (ffffffff81829f02)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_fail
  - io_uring/rw.c:io_read_mshot
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_complete_rw
  - io_uring/rw.c:io_req_rw_complete
```
```
In io_uring/waitid.c (ffffffff8182adc1)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_complete
```
```
In io_uring/futex.c (ffffffff8182faa5)
Location: io_uring/io_uring.h:189
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wake
  - io_uring/futex.c:io_futex_wait
  - io_uring/futex.c:io_futexv_wait
  - io_uring/futex.c:io_futexv_wait
  - io_uring/futex.c:io_futex_wake_fn
  - io_uring/futex.c:io_futex_wakev_fn
  - io_uring/futex.c:io_futexv_complete
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
