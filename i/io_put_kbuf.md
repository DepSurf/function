# Function: <code>io_put_kbuf</code>

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
In fs/io_uring.c (ffffffff81381fe5)
Location: fs/io_uring.c:1750
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_common
  - fs/io_uring.c:io_iopoll_complete
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
In fs/io_uring.c (ffffffff813934e9)
Location: fs/io_uring.c:2397
Inline: True
Inline callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_complete_rw_common
  - fs/io_uring.c:io_iopoll_complete
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
In fs/io_uring.c (ffffffff81396536)
Location: fs/io_uring.c:2236
Inline: True
Inline callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_iopoll_complete
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
In fs/io_uring.c (ffffffff813eafd6)
Location: fs/io_uring.c:2446
Inline: True
Inline callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_req_task_complete
  - fs/io_uring.c:io_iopoll_complete
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
In io_uring/io_uring.c (ffffffff816d1e7d)
Location: io_uring/io_uring.c:1457
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:io_req_complete_failed
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
In io_uring/io_uring.c (ffffffff8178d984)
Location: io_uring/kbuf.h:124
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/net.c (ffffffff81797290)
Location: io_uring/kbuf.h:124
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/rw.c (ffffffff817a4e46)
Location: io_uring/kbuf.h:124
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
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
In io_uring/io_uring.c (ffffffff817cf6a4)
Location: io_uring/kbuf.h:131
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/net.c (ffffffff817d7faa)
Location: io_uring/kbuf.h:131
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/rw.c (ffffffff817e5e08)
Location: io_uring/kbuf.h:131
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
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
In io_uring/io_uring.c (ffffffff818127e4)
Location: io_uring/kbuf.h:140
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_req_defer_failed
```
```
In io_uring/net.c (ffffffff8181c274)
Location: io_uring/kbuf.h:140
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/rw.c (ffffffff8182a07a)
Location: io_uring/kbuf.h:140
Inline: True
Inline callers:
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:io_read_mshot
  - io_uring/rw.c:kiocb_done
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
