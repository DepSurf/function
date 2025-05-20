# Function: <code>io_kbuf_recycle_legacy</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_kbuf_recycle_legacy(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff8179efb0)
Location: io_uring/kbuf.c:50
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/poll.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff8179efb0-ffffffff8179f056: io_kbuf_recycle_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_kbuf_recycle_legacy(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff817e0220)
Location: io_uring/kbuf.c:50
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/poll.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff817e0220-ffffffff817e02c6: io_kbuf_recycle_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool io_kbuf_recycle_legacy(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/kbuf.c (ffffffff81824670)
Location: io_uring/kbuf.c:78
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/rw.c:io_read_mshot
```
**Symbols:**

```
ffffffff81824670-ffffffff81824744: io_kbuf_recycle_legacy (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>
