# Function: <code>io_ring_submit_lock</code>

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
In fs/io_uring.c (ffffffff81387e5a)
Location: fs/io_uring.c:2324
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_provide_buffers
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
In fs/io_uring.c (ffffffff81393765)
Location: fs/io_uring.c:3075
Inline: True
Inline callers:
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_remove_buffers
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
In fs/io_uring.c (ffffffff813967ae)
Location: fs/io_uring.c:2877
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_provide_buffers
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
In fs/io_uring.c (ffffffff813e5ae2)
Location: fs/io_uring.c:3099
Inline: True
Inline callers:
  - fs/io_uring.c:io_rsrc_put_work
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_close
  - fs/io_uring.c:io_provide_buffers
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
In io_uring/io_uring.c (ffffffff816d70e8)
Location: io_uring/io_uring.c:1301
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_files_update
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_async_cancel
  - io_uring/io_uring.c:io_provide_buffers
  - io_uring/io_uring.c:io_remove_buffers
  - io_uring/io_uring.c:io_fixed_fd_install
  - io_uring/io_uring.c:io_splice
  - io_uring/io_uring.c:io_tee
  - io_uring/io_uring.c:io_buffer_select
  - io_uring/io_uring.c:io_kbuf_recycle
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
In io_uring/io_uring.c (ffffffff817913c9)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/filetable.c (ffffffff8179427c)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_install
```
```
In io_uring/openclose.c (ffffffff81794c5a)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
```
```
In io_uring/msg_ring.c (ffffffff81798bb4)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/poll.c (ffffffff8179e02a)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_cancel
```
```
In io_uring/cancel.c (ffffffff8179e46d)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff8179f9ae)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
```
```
In io_uring/rsrc.c (ffffffff817a1b10)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
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
In io_uring/io_uring.c (ffffffff817d262e)
Location: io_uring/io_uring.h:213
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/filetable.c (ffffffff817d4f6c)
Location: io_uring/io_uring.h:213
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_install
```
```
In io_uring/openclose.c (ffffffff817d58be)
Location: io_uring/io_uring.h:213
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
```
```
In io_uring/uring_cmd.c (0)
Location: io_uring/io_uring.h:213
Inline: True
```
```
In io_uring/net.c (0)
Location: io_uring/io_uring.h:213
Inline: True
```
```
In io_uring/msg_ring.c (ffffffff817d995c)
Location: io_uring/io_uring.h:213
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/poll.c (ffffffff817df190)
Location: io_uring/io_uring.h:213
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_cancel
```
```
In io_uring/cancel.c (ffffffff817df65d)
Location: io_uring/io_uring.h:213
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff817e0abe)
Location: io_uring/io_uring.h:213
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
```
```
In io_uring/rsrc.c (ffffffff817e2c9e)
Location: io_uring/io_uring.h:213
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (0)
Location: io_uring/io_uring.h:213
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
In io_uring/io_uring.c (ffffffff8181586e)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/filetable.c (ffffffff81818dbc)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_install
```
```
In io_uring/openclose.c (ffffffff81819715)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
```
```
In io_uring/uring_cmd.c (ffffffff81819a37)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_done
  - io_uring/uring_cmd.c:io_uring_cmd_mark_cancelable
```
```
In io_uring/net.c (0)
Location: io_uring/io_uring.h:214
Inline: True
```
```
In io_uring/msg_ring.c (ffffffff8181dc7c)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/poll.c (ffffffff81823574)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_cancel
```
```
In io_uring/cancel.c (ffffffff81823abd)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff81824fb0)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
```
```
In io_uring/rsrc.c (ffffffff81826bfe)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (0)
Location: io_uring/io_uring.h:214
Inline: True
```
```
In io_uring/waitid.c (ffffffff8182ac8a)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_cancel
```
```
In io_uring/futex.c (ffffffff8182f79f)
Location: io_uring/io_uring.h:214
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wait
  - io_uring/futex.c:io_futexv_wait
  - io_uring/futex.c:io_futex_cancel
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
