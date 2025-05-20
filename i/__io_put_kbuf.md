# Function: <code>__io_put_kbuf</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int __io_put_kbuf(struct io_kiocb *req, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c4cf0)
Location: io_uring/io_uring.c:1434
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_clean_op
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_poll_remove
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:kiocb_done
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:io_do_iopoll
  - io_uring/io_uring.c:handle_prev_tw_list
  - io_uring/io_uring.c:io_req_complete_failed
  - io_uring/io_uring.c:io_req_complete_failed
  - io_uring/io_uring.c:__io_req_complete_put
```
**Symbols:**

```
ffffffff816c4cf0-ffffffff816c4d62: __io_put_kbuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int __io_put_kbuf(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179f070)
Location: io_uring/kbuf.c:77
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_req_defer_failed
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
```
**Symbols:**

```
ffffffff8179f070-ffffffff8179f1cd: __io_put_kbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int __io_put_kbuf(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff817e02e0)
Location: io_uring/kbuf.c:77
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_req_defer_failed
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
```
**Symbols:**

```
ffffffff817e02e0-ffffffff817e043d: __io_put_kbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int __io_put_kbuf(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff81824760)
Location: io_uring/kbuf.c:105
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_req_defer_failed
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/rw.c:io_do_iopoll
  - io_uring/rw.c:io_read_mshot
  - io_uring/rw.c:kiocb_done
  - io_uring/rw.c:io_req_rw_complete
```
**Symbols:**

```
ffffffff81824760-ffffffff818248bd: __io_put_kbuf (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head *list</code>
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
