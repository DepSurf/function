# Function: <code>io_req_complete_post</code>

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
void io_req_complete_post(struct io_kiocb *req, long int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81395950)
Location: fs/io_uring.c:1606
Inline: False
Direct callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_req_complete_failed
```
**Symbols:**

```
ffffffff81395950-ffffffff81395c49: io_req_complete_post (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_req_complete_post(struct io_kiocb *req, long int res, unsigned int cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e95f0)
Location: fs/io_uring.c:1832
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqes
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:io_submit_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_drain_req
  - fs/io_uring.c:io_req_task_timeout
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_close
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_req_task_complete
  - fs/io_uring.c:io_req_task_cancel
```
**Symbols:**

```
ffffffff813e95f0-ffffffff813e991a: io_req_complete_post (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_req_complete_post(struct io_kiocb *req, s32 res, u32 cflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d02a0)
Location: io_uring/io_uring.c:2367
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_req_task_link_timeout
  - io_uring/io_uring.c:io_req_task_link_timeout
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_timeout_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_add
  - io_uring/io_uring.c:io_connect
  - io_uring/io_uring.c:io_socket
  - io_uring/io_uring.c:io_accept
  - io_uring/io_uring.c:io_recv
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
  - io_uring/io_uring.c:io_nop
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
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
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:io_req_tw_post
  - io_uring/io_uring.c:io_req_complete_failed
```
**Symbols:**

```
ffffffff816d02a0-ffffffff816d0369: io_req_complete_post (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_req_complete_post(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178e931)
Location: io_uring/io_uring.c:963
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/uring_cmd.c:io_uring_cmd_done
```
**Symbols:**

```
ffffffff8178e9c0-ffffffff8178ea50: io_req_complete_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_req_complete_post(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cf4c0)
Location: io_uring/io_uring.c:1023
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff817cf4c0-ffffffff817cf596: io_req_complete_post (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_req_complete_post(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81812600)
Location: io_uring/io_uring.c:1026
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81812600-ffffffff818126d6: io_req_complete_post (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int res</code> ➡️ <code>s32 res</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int cflags</code> ➡️ <code>u32 cflags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>s32 res</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 cflags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
