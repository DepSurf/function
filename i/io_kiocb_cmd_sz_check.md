# Function: <code>io_kiocb_cmd_sz_check</code>

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
In io_uring/xattr.c (ffffffff81792f01)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_fsetxattr_prep
  - io_uring/xattr.c:io_setxattr_prep
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/xattr.c:io_getxattr_prep
  - io_uring/xattr.c:__io_getxattr_prep
```
```
In io_uring/fs.c (ffffffff817936e5)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_linkat
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_cleanup
  - io_uring/fs.c:io_mkdirat
  - io_uring/fs.c:io_mkdirat_prep
  - io_uring/fs.c:io_unlinkat_cleanup
  - io_uring/fs.c:io_unlinkat
  - io_uring/fs.c:io_unlinkat_prep
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat
  - io_uring/fs.c:io_renameat_prep
```
```
In io_uring/splice.c (ffffffff817938f5)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_tee
  - io_uring/splice.c:io_tee_prep
```
```
In io_uring/sync.c (ffffffff81793c55)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
  - io_uring/sync.c:io_fallocate_prep
  - io_uring/sync.c:io_fsync
  - io_uring/sync.c:io_fsync_prep
  - io_uring/sync.c:io_sync_file_range
  - io_uring/sync.c:io_sfr_prep
```
```
In io_uring/advise.c (ffffffff81793e85)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
  - io_uring/advise.c:io_fadvise_prep
  - io_uring/advise.c:io_madvise
  - io_uring/advise.c:io_madvise_prep
```
```
In io_uring/openclose.c (ffffffff81794b6b)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_close_prep
  - io_uring/openclose.c:io_open_cleanup
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2_prep
  - io_uring/openclose.c:io_openat_prep
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/uring_cmd.c (ffffffff81794f95)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_prep
  - io_uring/uring_cmd.c:io_uring_cmd_prep_async
  - io_uring/uring_cmd.c:io_uring_cmd_work
```
```
In io_uring/epoll.c (ffffffff817951b5)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
  - io_uring/epoll.c:io_epoll_ctl_prep
```
```
In io_uring/statx.c (ffffffff81795365)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/statx.c:io_statx_cleanup
  - io_uring/statx.c:io_statx
  - io_uring/statx.c:io_statx_prep
```
```
In io_uring/net.c (ffffffff81798490)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect_prep
  - io_uring/net.c:io_connect_prep_async
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_accept_prep
  - io_uring/net.c:io_sendrecv_fail
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
  - io_uring/net.c:__io_recvmsg_copy_hdr
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg_prep
  - io_uring/net.c:io_sendmsg_prep_async
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_shutdown
  - io_uring/net.c:io_shutdown_prep
```
```
In io_uring/msg_ring.c (ffffffff81798a18)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring_prep
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/msg_ring.c:io_msg_ring_cleanup
```
```
In io_uring/timeout.c (ffffffff81799f4e)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/timeout.c:io_kill_timeouts
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove_prep
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_flush_timeouts
```
```
In io_uring/poll.c (ffffffff8179e119)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:io_poll_add_prep
  - io_uring/poll.c:io_poll_remove_prep
  - io_uring/poll.c:io_poll_queue_proc
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/cancel.c (ffffffff8179e69b)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
  - io_uring/cancel.c:io_async_cancel_prep
```
```
In io_uring/kbuf.c (ffffffff8179f9a3)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_provide_buffers_prep
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_remove_buffers_prep
```
```
In io_uring/rsrc.c (ffffffff817a1ae3)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update_prep
```
```
In io_uring/rw.c (ffffffff817a4d59)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_rw_init_file
  - io_uring/rw.c:io_async_buf_func
  - io_uring/rw.c:__io_import_iovec
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_prep_rw
```
```
In io_uring/notif.c (ffffffff817a5306)
Location: include/linux/io_uring_types.h:499
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
  - io_uring/notif.c:io_notif_set_extended
  - io_uring/notif.c:io_notif_complete_tw_ext
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
In io_uring/xattr.c (ffffffff817d3c6f)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_fsetxattr_prep
  - io_uring/xattr.c:io_setxattr_prep
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/xattr.c:io_getxattr_prep
  - io_uring/xattr.c:__io_getxattr_prep
```
```
In io_uring/fs.c (ffffffff817d43f5)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_linkat
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_cleanup
  - io_uring/fs.c:io_mkdirat
  - io_uring/fs.c:io_mkdirat_prep
  - io_uring/fs.c:io_unlinkat_cleanup
  - io_uring/fs.c:io_unlinkat
  - io_uring/fs.c:io_unlinkat_prep
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat
  - io_uring/fs.c:io_renameat_prep
```
```
In io_uring/splice.c (ffffffff817d4625)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_tee
  - io_uring/splice.c:io_tee_prep
```
```
In io_uring/sync.c (ffffffff817d4975)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
  - io_uring/sync.c:io_fallocate_prep
  - io_uring/sync.c:io_fsync
  - io_uring/sync.c:io_fsync_prep
  - io_uring/sync.c:io_sync_file_range
  - io_uring/sync.c:io_sfr_prep
```
```
In io_uring/advise.c (ffffffff817d4bd5)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
  - io_uring/advise.c:io_fadvise_prep
  - io_uring/advise.c:io_madvise
  - io_uring/advise.c:io_madvise_prep
```
```
In io_uring/openclose.c (ffffffff817d57cb)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_close_prep
  - io_uring/openclose.c:io_open_cleanup
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2_prep
  - io_uring/openclose.c:io_openat_prep
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/uring_cmd.c (ffffffff817d5ca5)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_prep
  - io_uring/uring_cmd.c:io_uring_cmd_prep_async
  - io_uring/uring_cmd.c:io_uring_cmd_work
```
```
In io_uring/epoll.c (ffffffff817d5ea5)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
  - io_uring/epoll.c:io_epoll_ctl_prep
```
```
In io_uring/statx.c (ffffffff817d6045)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/statx.c:io_statx_cleanup
  - io_uring/statx.c:io_statx
  - io_uring/statx.c:io_statx_prep
```
```
In io_uring/net.c (ffffffff817d9220)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect_prep
  - io_uring/net.c:io_connect_prep_async
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_accept_prep
  - io_uring/net.c:io_sendrecv_fail
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep
  - io_uring/net.c:__io_compat_recvmsg_copy_hdr
  - io_uring/net.c:__io_recvmsg_copy_hdr
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg_prep
  - io_uring/net.c:io_sendmsg_prep_async
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_shutdown
  - io_uring/net.c:io_shutdown_prep
```
```
In io_uring/msg_ring.c (ffffffff817d9ae5)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring_prep
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/msg_ring.c:io_msg_ring_cleanup
```
```
In io_uring/timeout.c (ffffffff817dae55)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove_prep
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_timeout_complete
```
```
In io_uring/poll.c (ffffffff817df36c)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:io_poll_add_prep
  - io_uring/poll.c:io_poll_remove_prep
  - io_uring/poll.c:io_poll_queue_proc
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/cancel.c (ffffffff817df88b)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
  - io_uring/cancel.c:io_async_cancel_prep
```
```
In io_uring/kbuf.c (ffffffff817e0ab3)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_provide_buffers_prep
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_remove_buffers_prep
```
```
In io_uring/rsrc.c (ffffffff817e2d5f)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update_prep
```
```
In io_uring/rw.c (ffffffff817e5d27)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_rw_init_file
  - io_uring/rw.c:io_async_buf_func
  - io_uring/rw.c:__io_import_iovec
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_prep_rw
```
```
In io_uring/notif.c (ffffffff817e62d6)
Location: include/linux/io_uring_types.h:517
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
  - io_uring/notif.c:io_notif_set_extended
  - io_uring/notif.c:io_notif_complete_tw_ext
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
In io_uring/io_uring.c (ffffffff81814014)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
```
```
In io_uring/xattr.c (ffffffff81817aff)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_setxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_fsetxattr
  - io_uring/xattr.c:io_fsetxattr_prep
  - io_uring/xattr.c:io_setxattr_prep
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_getxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/xattr.c:io_fgetxattr
  - io_uring/xattr.c:io_getxattr_prep
  - io_uring/xattr.c:__io_getxattr_prep
```
```
In io_uring/fs.c (ffffffff81818265)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/fs.c:io_link_cleanup
  - io_uring/fs.c:io_linkat
  - io_uring/fs.c:io_linkat_prep
  - io_uring/fs.c:io_symlinkat
  - io_uring/fs.c:io_symlinkat_prep
  - io_uring/fs.c:io_mkdirat_cleanup
  - io_uring/fs.c:io_mkdirat
  - io_uring/fs.c:io_mkdirat_prep
  - io_uring/fs.c:io_unlinkat_cleanup
  - io_uring/fs.c:io_unlinkat
  - io_uring/fs.c:io_unlinkat_prep
  - io_uring/fs.c:io_renameat_cleanup
  - io_uring/fs.c:io_renameat
  - io_uring/fs.c:io_renameat_prep
```
```
In io_uring/splice.c (ffffffff81818495)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/splice.c:io_splice
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_splice_prep
  - io_uring/splice.c:io_tee
  - io_uring/splice.c:io_tee_prep
```
```
In io_uring/sync.c (ffffffff818187e5)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/sync.c:io_fallocate
  - io_uring/sync.c:io_fallocate_prep
  - io_uring/sync.c:io_fsync
  - io_uring/sync.c:io_fsync_prep
  - io_uring/sync.c:io_sync_file_range
  - io_uring/sync.c:io_sfr_prep
```
```
In io_uring/advise.c (ffffffff81818a35)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/advise.c:io_fadvise
  - io_uring/advise.c:io_fadvise_prep
  - io_uring/advise.c:io_madvise
  - io_uring/advise.c:io_madvise_prep
```
```
In io_uring/openclose.c (ffffffff81819825)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/openclose.c:io_install_fixed_fd
  - io_uring/openclose.c:io_install_fixed_fd_prep
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_close
  - io_uring/openclose.c:io_close_prep
  - io_uring/openclose.c:io_open_cleanup
  - io_uring/openclose.c:io_openat2
  - io_uring/openclose.c:io_openat2_prep
  - io_uring/openclose.c:io_openat_prep
  - io_uring/openclose.c:__io_openat_prep
```
```
In io_uring/uring_cmd.c (ffffffff81819f15)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd_prep
  - io_uring/uring_cmd.c:io_uring_cmd_prep_async
  - io_uring/uring_cmd.c:io_uring_cmd_work
```
```
In io_uring/epoll.c (ffffffff8181a105)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/epoll.c:io_epoll_ctl
  - io_uring/epoll.c:io_epoll_ctl_prep
```
```
In io_uring/statx.c (ffffffff8181a2a5)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/statx.c:io_statx_cleanup
  - io_uring/statx.c:io_statx
  - io_uring/statx.c:io_statx_prep
```
```
In io_uring/net.c (ffffffff8181d52b)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect_prep
  - io_uring/net.c:io_connect_prep_async
  - io_uring/net.c:io_socket
  - io_uring/net.c:io_socket_prep
  - io_uring/net.c:io_accept
  - io_uring/net.c:io_accept_prep
  - io_uring/net.c:io_sendrecv_fail
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg_prep
  - io_uring/net.c:io_sendmsg_prep_async
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_shutdown
  - io_uring/net.c:io_shutdown_prep
```
```
In io_uring/msg_ring.c (ffffffff8181de05)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring_prep
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_install_complete
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/msg_ring.c:io_msg_ring_cleanup
```
```
In io_uring/timeout.c (ffffffff8181f145)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/timeout.c:io_queue_linked_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:io_timeout
  - io_uring/timeout.c:__io_timeout_prep
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove
  - io_uring/timeout.c:io_timeout_remove_prep
  - io_uring/timeout.c:io_link_timeout_fn
  - io_uring/timeout.c:io_req_task_link_timeout
  - io_uring/timeout.c:io_timeout_extract
  - io_uring/timeout.c:io_timeout_fn
  - io_uring/timeout.c:io_disarm_next
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_flush_timeouts
  - io_uring/timeout.c:io_timeout_complete
```
```
In io_uring/poll.c (ffffffff81823750)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_add
  - io_uring/poll.c:io_poll_add_prep
  - io_uring/poll.c:io_poll_remove_prep
  - io_uring/poll.c:io_poll_queue_proc
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/cancel.c (ffffffff81823d0b)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/cancel.c:io_async_cancel
  - io_uring/cancel.c:io_async_cancel_prep
```
```
In io_uring/kbuf.c (ffffffff81824f9e)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_provide_buffers_prep
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_remove_buffers_prep
```
```
In io_uring/rsrc.c (ffffffff81826cbf)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
  - io_uring/rsrc.c:io_files_update_prep
```
```
In io_uring/rw.c (ffffffff8182a00b)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read_mshot
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:io_rw_init_file
  - io_uring/rw.c:io_async_buf_func
  - io_uring/rw.c:__io_import_iovec
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
  - io_uring/rw.c:io_read_mshot_prep
  - io_uring/rw.c:io_prep_rwv
  - io_uring/rw.c:io_prep_rw
```
```
In io_uring/notif.c (ffffffff8182a4f6)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
  - io_uring/notif.c:io_notif_set_extended
  - io_uring/notif.c:io_notif_complete_tw_ext
```
```
In io_uring/waitid.c (ffffffff8182ac38)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_prep
  - io_uring/waitid.c:io_waitid_wait
  - io_uring/waitid.c:io_waitid_cb
  - io_uring/waitid.c:io_waitid_cb
  - io_uring/waitid.c:io_waitid_complete
  - io_uring/waitid.c:io_waitid_copy_si
```
```
In io_uring/futex.c (ffffffff8182fa65)
Location: include/linux/io_uring_types.h:564
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wake
  - io_uring/futex.c:io_futex_wait
  - io_uring/futex.c:io_futexv_wait
  - io_uring/futex.c:io_futexv_prep
  - io_uring/futex.c:io_futex_wakev_fn
  - io_uring/futex.c:io_futex_prep
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
