# Function: <code>__io_recvmsg_copy_hdr</code>

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
int __io_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_ctx *io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137b830)
Location: fs/io_uring.c:3714
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_recvmsg_prep
```
**Symbols:**

```
ffffffff8137b830-ffffffff8137b938: __io_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __io_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81389bc0)
Location: fs/io_uring.c:4722
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff81389bc0-ffffffff81389ccb: __io_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __io_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390980)
Location: fs/io_uring.c:4460
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff81390980-ffffffff81390a6d: __io_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __io_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ddf30)
Location: fs/io_uring.c:4892
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff813ddf30-ffffffff813de01d: __io_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __io_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816c8360)
Location: io_uring/io_uring.c:6017
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff816c8360-ffffffff816c8473: __io_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __io_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817956a0)
Location: io_uring/net.c:432
Inline: False
Direct callers:
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep_async
```
**Symbols:**

```
ffffffff817956a0-ffffffff8179582b: __io_recvmsg_copy_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __io_recvmsg_copy_hdr(struct io_kiocb *req, struct io_async_msghdr *iomsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817d6280)
Location: io_uring/net.c:441
Inline: False
Direct callers:
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep_async
```
**Symbols:**

```
ffffffff817d6280-ffffffff817d640b: __io_recvmsg_copy_hdr (STB_LOCAL)
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
In io_uring/net.c (ffffffff8181a840)
Location: io_uring/net.c:453
Inline: True
Direct callers:
  - io_uring/net.c:io_recvmsg
  - io_uring/net.c:io_recvmsg_prep_async
```
**Symbols:**

```
ffffffff8181a840-ffffffff8181a9cb: __io_recvmsg_copy_hdr.constprop.0 (STB_LOCAL)
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
