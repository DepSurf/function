# Function: <code>sendmsg_copy_msghdr</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819103ac)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sendmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2630)
Location: net/socket.c:2371
Inline: False
Direct callers:
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_sendmsg_prep
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff819e2630-ffffffff819e26ca: sendmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sendmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e22b0)
Location: net/socket.c:2364
Inline: False
Direct callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:io_sendmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff819e22b0-ffffffff819e234a: sendmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sendmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c8340)
Location: net/socket.c:2358
Inline: False
Direct callers:
  - fs/io_uring.c:io_sendmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff819c8340-ffffffff819c83d4: sendmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sendmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a77690)
Location: net/socket.c:2431
Inline: False
Direct callers:
  - fs/io_uring.c:io_sendmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81a77690-ffffffff81a77724: sendmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sendmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81beaa10)
Location: net/socket.c:2507
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_sendmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff81beaa10-ffffffff81beaacb: sendmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d97372)
Location: net/socket.c:2495
Inline: True
Inline callers:
  - net/socket.c:___sys_sendmsg
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg_prep_async
```
**Symbols:**

```
ffffffff81d97410-ffffffff81d97456: sendmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e059e2)
Location: net/socket.c:2533
Inline: True
Inline callers:
  - net/socket.c:___sys_sendmsg
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg_prep_async
```
**Symbols:**

```
ffffffff81e05a80-ffffffff81e05ac6: sendmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sendmsg_copy_msghdr(struct msghdr *msg, struct user_msghdr *umsg, unsigned int flags, struct iovec **iov);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec22a2)
Location: net/socket.c:2603
Inline: True
Inline callers:
  - net/socket.c:___sys_sendmsg
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg
  - io_uring/net.c:io_sendmsg_prep_async
```
**Symbols:**

```
ffffffff81ec2340-ffffffff81ec2386: sendmsg_copy_msghdr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba83dc)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc703c)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7cbd0)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073bd9a)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818b03ac)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186a2fc)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819013ac)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8192239c)
Location: net/socket.c:2316
Inline: True
Inline callers:
  - net/socket.c:__sys_sendmsg_sock
  - net/socket.c:___sys_sendmsg
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
