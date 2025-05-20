# Function: <code>__io_compat_recvmsg_copy_hdr</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int __io_compat_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_ctx *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137b730)
Location: fs/io_uring.c:3746
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_recvmsg_prep
```
**Symbols:**

```
ffffffff8137b730-ffffffff8137b82f: __io_compat_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __io_compat_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389ad0)
Location: fs/io_uring.c:4756
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff81389ad0-ffffffff81389bc0: __io_compat_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __io_compat_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390890)
Location: fs/io_uring.c:4493
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff81390890-ffffffff8139097e: __io_compat_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __io_compat_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813dde40)
Location: fs/io_uring.c:4925
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff813dde40-ffffffff813ddf2e: __io_compat_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __io_compat_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c8240)
Location: io_uring/io_uring.c:6050
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff816c8240-ffffffff816c8357: __io_compat_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_compat_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff81795510)
Location: io_uring/net.c:479
Inline: False
Direct callers:
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep_async
```
**Symbols:**

```
ffffffff81795510-ffffffff81795690: __io_compat_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __io_compat_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817d6110)
Location: io_uring/net.c:488
Inline: False
Direct callers:
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep_async
```
**Symbols:**

```
ffffffff817d6110-ffffffff817d626b: __io_compat_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In io_uring/net.c (ffffffff8181a6d0)
Location: io_uring/net.c:500
Inline: True
Direct callers:
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep_async
```
**Symbols:**

```
ffffffff8181a6d0-ffffffff8181a82b: __io_compat_recvmsg_copy_hdr.constprop.0 (STB_LOCAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct io_async_msghdr *iomsg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct io_async_ctx *io</code>
</li>
</ul>
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
