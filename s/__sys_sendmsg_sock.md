# Function: <code>__sys_sendmsg_sock</code>

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
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818de2e0)
Location: net/socket.c:2334
Inline: False
```
**Symbols:**

```
ffffffff818de2e0-ffffffff818de325: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81910340)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
ffffffff81910340-ffffffff81910422: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2790)
Location: net/socket.c:2415
Inline: False
Direct callers:
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff819e2790-ffffffff819e27bd: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e2410)
Location: net/socket.c:2408
Inline: False
Direct callers:
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff819e2410-ffffffff819e243d: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c84a0)
Location: net/socket.c:2402
Inline: False
Direct callers:
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff819c84a0-ffffffff819c84b7: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a777f0)
Location: net/socket.c:2475
Inline: False
Direct callers:
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff81a777f0-ffffffff81a77807: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81beabb0)
Location: net/socket.c:2551
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_sendmsg
```
**Symbols:**

```
ffffffff81beabb0-ffffffff81beabd6: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d97470)
Location: net/socket.c:2539
Inline: False
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg
```
**Symbols:**

```
ffffffff81d97470-ffffffff81d97496: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e05ae0)
Location: net/socket.c:2577
Inline: False
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg
```
**Symbols:**

```
ffffffff81e05ae0-ffffffff81e05b06: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct msghdr *msg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec23a0)
Location: net/socket.c:2647
Inline: False
Direct callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg
```
**Symbols:**

```
ffffffff81ec23a0-ffffffff81ec23c6: __sys_sendmsg_sock (STB_GLOBAL)
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
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba8398)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
ffff800010ba8398-ffff800010ba8488: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6fd4)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
c0cc6fd4-c0cc70b0: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7cb50)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
c000000000c7cb50-c000000000c7cc84: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073bd78)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
ffffffe00073bd78-ffffffe00073be2a: __sys_sendmsg_sock (STB_GLOBAL)
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
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818b0340)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
ffffffff818b0340-ffffffff818b0422: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186a290)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
ffffffff8186a290-ffffffff8186a372: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81901340)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
ffffffff81901340-ffffffff81901422: __sys_sendmsg_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __sys_sendmsg_sock(struct socket *sock, struct user_msghdr *umsg, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81922330)
Location: net/socket.c:2360
Inline: False
```
**Symbols:**

```
ffffffff81922330-ffffffff81922412: __sys_sendmsg_sock (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct user_msghdr *umsg</code>
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
