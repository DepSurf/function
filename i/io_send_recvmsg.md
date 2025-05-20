# Function: <code>io_send_recvmsg</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132e400)
Location: fs/io_uring.c:1474
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff8132e400-ffffffff8132e4e0: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813420b0)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff813420b0-ffffffff81342212: io_send_recvmsg (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010401c28)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffff800010401c28-ffff800010401de8: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d39ec)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
c05d39ec-c05d3b78: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050b7f0)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
c00000000050b7f0-c00000000050ba60: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ae5d8)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffe0002ae5d8-ffffffe0002ae73a: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133a690)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff8133a690-ffffffff8133a7f2: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132b3a0)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff8132b3a0-ffffffff8132b502: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81338160)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff81338160-ffffffff813382c2: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_send_recvmsg(struct io_kiocb *req, const struct io_uring_sqe *sqe, bool force_nonblock, long int (*fn)(struct socket *, struct user_msghdr *, unsigned int));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134ad70)
Location: fs/io_uring.c:1638
Inline: False
Direct callers:
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
```
**Symbols:**

```
ffffffff8134ad70-ffffffff8134aecb: io_send_recvmsg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
