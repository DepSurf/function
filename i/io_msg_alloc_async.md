# Function: <code>io_msg_alloc_async</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct io_async_msghdr *io_msg_alloc_async(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817966d5)
Location: io_uring/net.c:135
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
Direct callers:
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_setup_async_msg
```
**Symbols:**

```
ffffffff81795440-ffffffff817954f5: io_msg_alloc_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct io_async_msghdr *io_msg_alloc_async(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817d73d5)
Location: io_uring/net.c:137
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
Direct callers:
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_setup_async_msg
```
**Symbols:**

```
ffffffff817d6540-ffffffff817d65d2: io_msg_alloc_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct io_async_msghdr *io_msg_alloc_async(struct io_kiocb *req, unsigned int issue_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff8181b645)
Location: io_uring/net.c:145
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_recvmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
  - io_uring/net.c:io_sendmsg_prep_async
Direct callers:
  - io_uring/net.c:io_setup_async_addr
  - io_uring/net.c:io_send_prep_async
  - io_uring/net.c:io_setup_async_msg
```
**Symbols:**

```
ffffffff8181a3f0-ffffffff8181a482: io_msg_alloc_async (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
