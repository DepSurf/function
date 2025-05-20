# Function: <code>io_req_complete_state</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139f2fb)
Location: fs/io_uring.c:1650
Inline: True
Inline callers:
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
In fs/io_uring.c (ffffffff813ed0bc)
Location: fs/io_uring.c:1874
Inline: True
Inline callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
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
In io_uring/io_uring.c (ffffffff816d4e57)
Location: io_uring/io_uring.c:2378
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_files_update
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
  - io_uring/io_uring.c:io_close
  - io_uring/io_uring.c:io_fadvise
  - io_uring/io_uring.c:io_epoll_ctl
  - io_uring/io_uring.c:io_provide_buffers
  - io_uring/io_uring.c:io_remove_buffers
  - io_uring/io_uring.c:io_openat2
  - io_uring/io_uring.c:io_msg_ring
  - io_uring/io_uring.c:io_nop
  - io_uring/io_uring.c:kiocb_done
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
