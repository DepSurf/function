# Function: <code>io_kbuf_recycle</code>

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
void io_kbuf_recycle(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816ced00)
Location: io_uring/io_uring.c:1504
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff816ced00-ffffffff816cedf7: io_kbuf_recycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void io_kbuf_recycle(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81790434)
Location: io_uring/kbuf.h:87
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
```
```
In io_uring/net.c (ffffffff8179751f)
Location: io_uring/kbuf.h:87
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
Direct callers:
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/poll.c (ffffffff8179da48)
Location: io_uring/kbuf.h:87
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff81795840-ffffffff817958c9: io_kbuf_recycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void io_kbuf_recycle(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cf814)
Location: io_uring/kbuf.h:94
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
```
```
In io_uring/net.c (ffffffff817d826d)
Location: io_uring/kbuf.h:94
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
Direct callers:
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/poll.c (ffffffff817dec6d)
Location: io_uring/kbuf.h:94
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
**Symbols:**

```
ffffffff817d6420-ffffffff817d64a9: io_kbuf_recycle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (ffffffff81812954)
Location: io_uring/kbuf.h:102
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_queue_async
  - io_uring/io_uring.c:io_queue_async
```
```
In io_uring/net.c (ffffffff8181c56f)
Location: io_uring/kbuf.h:102
Inline: True
Inline callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
Direct callers:
  - io_uring/net.c:io_recvmsg
```
```
In io_uring/poll.c (ffffffff8182300e)
Location: io_uring/kbuf.h:102
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
```
```
In io_uring/rw.c (ffffffff81829a26)
Location: io_uring/kbuf.h:102
Inline: True
Inline callers:
  - io_uring/rw.c:io_read_mshot
```
**Symbols:**

```
ffffffff8181ad30-ffffffff8181adaa: io_kbuf_recycle.isra.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
