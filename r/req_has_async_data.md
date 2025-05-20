# Function: <code>req_has_async_data</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d55ed)
Location: io_uring/io_uring.c:1615
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_timeout_prep
  - io_uring/io_uring.c:io_connect
  - io_uring/io_uring.c:io_connect
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_sendmsg
  - io_uring/io_uring.c:io_uring_cmd
  - io_uring/io_uring.c:io_uring_cmd
  - io_uring/io_uring.c:io_write
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_setup_async_rw
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:kiocb_done
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
In io_uring/io_uring.c (ffffffff81791017)
Location: io_uring/io_uring.h:187
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_prep_async
```
```
In io_uring/uring_cmd.c (ffffffff81795006)
Location: io_uring/io_uring.h:187
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
  - io_uring/uring_cmd.c:io_uring_cmd
```
```
In io_uring/net.c (ffffffff817984a7)
Location: io_uring/io_uring.h:187
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_setup_async_msg
  - io_uring/net.c:io_netmsg_recycle
```
```
In io_uring/timeout.c (ffffffff8179922d)
Location: io_uring/io_uring.h:187
Inline: True
Inline callers:
  - io_uring/timeout.c:__io_timeout_prep
```
```
In io_uring/rw.c (ffffffff817a4c1f)
Location: io_uring/io_uring.h:187
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_fail
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_setup_async_rw
  - io_uring/rw.c:kiocb_done
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
In io_uring/io_uring.c (ffffffff817d1cfb)
Location: io_uring/io_uring.h:194
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_prep_async
```
```
In io_uring/uring_cmd.c (ffffffff817d5da1)
Location: io_uring/io_uring.h:194
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
```
```
In io_uring/net.c (ffffffff817d9237)
Location: io_uring/io_uring.h:194
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_setup_async_msg
  - io_uring/net.c:io_netmsg_recycle
```
```
In io_uring/timeout.c (ffffffff817da2cf)
Location: io_uring/io_uring.h:194
Inline: True
Inline callers:
  - io_uring/timeout.c:__io_timeout_prep
```
```
In io_uring/rw.c (ffffffff817e5bef)
Location: io_uring/io_uring.h:194
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_fail
  - io_uring/rw.c:io_write
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_setup_async_rw
  - io_uring/rw.c:kiocb_done
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
In io_uring/io_uring.c (ffffffff818140ba)
Location: io_uring/io_uring.h:195
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_req_prep_async
```
```
In io_uring/uring_cmd.c (ffffffff8181a009)
Location: io_uring/io_uring.h:195
Inline: True
Inline callers:
  - io_uring/uring_cmd.c:io_uring_cmd
```
```
In io_uring/net.c (ffffffff8181d52e)
Location: io_uring/io_uring.h:195
Inline: True
Inline callers:
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_connect
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_cleanup
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_send
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_setup_async_msg
  - io_uring/net.c:io_netmsg_recycle
```
```
In io_uring/timeout.c (ffffffff8181e5bf)
Location: io_uring/io_uring.h:195
Inline: True
Inline callers:
  - io_uring/timeout.c:__io_timeout_prep
```
```
In io_uring/rw.c (ffffffff81829edf)
Location: io_uring/io_uring.h:195
Inline: True
Inline callers:
  - io_uring/rw.c:io_rw_fail
  - io_uring/rw.c:io_write
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:io_setup_async_rw
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_complete_rw
  - io_uring/rw.c:io_req_rw_complete
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
