# Function: <code>io_setup_async_msg</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int io_setup_async_msg(struct io_kiocb *req, struct io_async_msghdr *kmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137d540)
Location: fs/io_uring.c:3569
Inline: True
Direct callers:
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff8137d540-ffffffff8137d604: io_setup_async_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int io_setup_async_msg(struct io_kiocb *req, struct io_async_msghdr *kmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138d400)
Location: fs/io_uring.c:4572
Inline: True
Direct callers:
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff8138d400-ffffffff8138d4c9: io_setup_async_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int io_setup_async_msg(struct io_kiocb *req, struct io_async_msghdr *kmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139b1e0)
Location: fs/io_uring.c:4315
Inline: True
Direct callers:
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff8139b1e0-ffffffff8139b27b: io_setup_async_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int io_setup_async_msg(struct io_kiocb *req, struct io_async_msghdr *kmsg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e43b0)
Location: fs/io_uring.c:4747
Inline: True
Direct callers:
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff813e43b0-ffffffff813e4496: io_setup_async_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_setup_async_msg(struct io_kiocb *req, struct io_async_msghdr *kmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d7c20)
Location: io_uring/io_uring.c:5837
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff816d7c20-ffffffff816d7cdb: io_setup_async_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_setup_async_msg(struct io_kiocb *req, struct io_async_msghdr *kmsg, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff81795960)
Location: io_uring/net.c:167
Inline: False
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_sendmsg
```
**Symbols:**

```
ffffffff81795960-ffffffff81795a61: io_setup_async_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_setup_async_msg(struct io_kiocb *req, struct io_async_msghdr *kmsg, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817d65f0)
Location: io_uring/net.c:169
Inline: False
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_sendmsg
```
**Symbols:**

```
ffffffff817d65f0-ffffffff817d66fc: io_setup_async_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_setup_async_msg(struct io_kiocb *req, struct io_async_msghdr *kmsg, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff8181a4a0)
Location: io_uring/net.c:177
Inline: False
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_sendmsg
```
**Symbols:**

```
ffffffff8181a4a0-ffffffff8181a5be: io_setup_async_msg (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int issue_flags</code>
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
