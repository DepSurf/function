# Function: <code>__sys_recvmsg_sock</code>

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
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818de680)
Location: net/socket.c:2515
Inline: False
```
**Symbols:**

```
ffffffff818de680-ffffffff818de6c2: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819107a0)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
ffffffff819107a0-ffffffff81910894: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct msghdr *msg, struct user_msghdr *umsg, struct sockaddr *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2b90)
Location: net/socket.c:2626
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff819e2b90-ffffffff819e2bbb: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct msghdr *msg, struct user_msghdr *umsg, struct sockaddr *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e27f0)
Location: net/socket.c:2619
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff819e27f0-ffffffff819e2835: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct msghdr *msg, struct user_msghdr *umsg, struct sockaddr *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c8850)
Location: net/socket.c:2609
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff819c8850-ffffffff819c8865: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct msghdr *msg, struct user_msghdr *umsg, struct sockaddr *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a77ba0)
Location: net/socket.c:2682
Inline: False
Direct callers:
  - fs/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff81a77ba0-ffffffff81a77bb5: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct msghdr *msg, struct user_msghdr *umsg, struct sockaddr *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81beb060)
Location: net/socket.c:2758
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_recvmsg
  - io_uring/io_uring.c:io_recvmsg
```
**Symbols:**

```
ffffffff81beb060-ffffffff81beb087: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct msghdr *msg, struct user_msghdr *umsg, struct sockaddr *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d979a0)
Location: net/socket.c:2746
Inline: False
Direct callers:
  - io_uring/net.c:io_recvmsg
```
**Symbols:**

```
ffffffff81d979a0-ffffffff81d979c7: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct msghdr *msg, struct user_msghdr *umsg, struct sockaddr *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e06010)
Location: net/socket.c:2784
Inline: False
Direct callers:
  - io_uring/net.c:io_recvmsg
```
**Symbols:**

```
ffffffff81e06010-ffffffff81e06037: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct msghdr *msg, struct user_msghdr *umsg, struct sockaddr *uaddr, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec28d0)
Location: net/socket.c:2854
Inline: False
Direct callers:
  - io_uring/net.c:io_recvmsg
```
**Symbols:**

```
ffffffff81ec28d0-ffffffff81ec28f7: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba89d0)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
ffff800010ba89d0-ffff800010ba8acc: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc7338)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
c0cc7338-c0cc741c: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7d1b0)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
c000000000c7d1b0-c000000000c7d2e8: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073c070)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
ffffffe00073c070-ffffffe00073c12a: __sys_recvmsg_sock (STB_GLOBAL)
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
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818b07a0)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
ffffffff818b07a0-ffffffff818b0894: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186a6f0)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
ffffffff8186a6f0-ffffffff8186a7e4: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819017a0)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
ffffffff819017a0-ffffffff81901894: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __sys_recvmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81922740)
Location: net/socket.c:2579
Inline: False
```
**Symbols:**

```
ffffffff81922740-ffffffff81922834: __sys_recvmsg_sock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_msghdr *umsg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_msghdr *msg</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct msghdr *msg</code>
</li>
<li>
<b>Param added. </b>
<code>struct sockaddr *uaddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>sock, umsg, flags</code> ➡️ <code>sock, msg, umsg, uaddr, flags</code>
</li>
</ul>
</details>
</li>
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
