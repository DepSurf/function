# Function: <code>io_ring_submit_unlock</code>

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
In fs/io_uring.c (ffffffff81384213)
Location: fs/io_uring.c:2318
Inline: True
Inline callers:
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
In fs/io_uring.c (ffffffff81393837)
Location: fs/io_uring.c:3069
Inline: True
Inline callers:
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_remove_buffers
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
In fs/io_uring.c (ffffffff8139675c)
Location: fs/io_uring.c:2871
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
In fs/io_uring.c (ffffffff813e5b38)
Location: fs/io_uring.c:3093
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
In io_uring/io_uring.c (ffffffff816d7151)
Location: io_uring/io_uring.c:1294
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
In io_uring/io_uring.c (ffffffff8179141f)
Location: io_uring/io_uring.h:198
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
```
```
In io_uring/filetable.c (ffffffff8179428d)
Location: io_uring/io_uring.h:198
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_install
```
```
In io_uring/openclose.c (ffffffff81794c6a)
Location: io_uring/io_uring.h:198
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
```
```
In io_uring/msg_ring.c (ffffffff81798be8)
Location: io_uring/io_uring.h:198
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/poll.c (ffffffff8179e06b)
Location: io_uring/io_uring.h:198
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_cancel
```
```
In io_uring/cancel.c (ffffffff8179e4bb)
Location: io_uring/io_uring.h:198
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff8179f9e2)
Location: io_uring/io_uring.h:198
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
```
```
In io_uring/rsrc.c (ffffffff817a1b4c)
Location: io_uring/io_uring.h:198
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
In io_uring/io_uring.c (ffffffff817d27dc)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/filetable.c (ffffffff817d4f7d)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_install
```
```
In io_uring/openclose.c (ffffffff817d58ce)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
```
```
In io_uring/uring_cmd.c (ffffffff817d5c47)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_prep
```
```
In io_uring/net.c (ffffffff817d853e)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/net.c:io_send_zc_prep
```
```
In io_uring/msg_ring.c (ffffffff817d9993)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/poll.c (ffffffff817df1d6)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_cancel
```
```
In io_uring/cancel.c (ffffffff817df6a6)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff817e0af1)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
```
```
In io_uring/rsrc.c (ffffffff817e2cbf)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (ffffffff817e50a5)
Location: io_uring/io_uring.h:205
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw
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
In io_uring/io_uring.c (ffffffff818158c7)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_wq_submit_work
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/io_uring.c:__io_req_complete_post
```
```
In io_uring/filetable.c (ffffffff81818dcd)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/filetable.c:io_fixed_fd_install
```
```
In io_uring/openclose.c (ffffffff81819725)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/openclose.c:io_close
```
```
In io_uring/uring_cmd.c (ffffffff81819eb7)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd_prep
  - io_uring/uring_cmd.c:io_uring_cmd_done
  - io_uring/uring_cmd.c:io_uring_cmd_mark_cancelable
```
```
In io_uring/net.c (ffffffff8181c84e)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/net.c:io_send_zc_prep
```
```
In io_uring/msg_ring.c (ffffffff8181dcb3)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
```
```
In io_uring/poll.c (ffffffff818235ba)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_remove
  - io_uring/poll.c:io_poll_cancel
```
```
In io_uring/cancel.c (ffffffff81823b06)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/cancel.c:__io_async_cancel
```
```
In io_uring/kbuf.c (ffffffff81824fe5)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
  - io_uring/kbuf.c:io_remove_buffers
  - io_uring/kbuf.c:io_buffer_select
  - io_uring/kbuf.c:io_kbuf_recycle_legacy
```
```
In io_uring/rsrc.c (ffffffff81826c1f)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_files_update
```
```
In io_uring/rw.c (ffffffff818296a1)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/rw.c:io_prep_rw_fixed
```
```
In io_uring/waitid.c (ffffffff8182adb7)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid
  - io_uring/waitid.c:io_waitid_cancel
```
```
In io_uring/futex.c (ffffffff8182f8c1)
Location: io_uring/io_uring.h:206
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wait
  - io_uring/futex.c:io_futex_wait
  - io_uring/futex.c:io_futexv_wait
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
