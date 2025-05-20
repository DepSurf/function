# Function: <code>sock_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fe060)
Location: net/socket.c:616
Inline: False
Direct callers:
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
  - net/socket.c:SYSC_sendto
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_sendmsg
```
**Symbols:**

```
ffffffff816fe060-ffffffff816fe0a1: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764a50)
Location: net/socket.c:614
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:SYSC_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81764a50-ffffffff81764a91: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81791ad0)
Location: net/socket.c:640
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:SYSC_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81791ad0-ffffffff81791b11: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b0010)
Location: net/socket.c:638
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:SYSC_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff817b0010-ffffffff817b0051: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81828190)
Location: net/socket.c:643
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:SYSC_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81828190-ffffffff818281d7: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81870f90)
Location: net/socket.c:647
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81870f90-ffffffff81870fd7: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818921a0)
Location: net/socket.c:627
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff818921a0-ffffffff818921e7: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dc300)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:___sys_sendmsg
  - net/socket.c:___sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff818dc300-ffffffff818dc367: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190dea0)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff8190dea0-ffffffff8190df07: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df9c0)
Location: net/socket.c:667
Inline: False
Direct callers:
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_send
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff819df9c0-ffffffff819dfa27: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df180)
Location: net/socket.c:667
Inline: False
Direct callers:
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_send
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff819df180-ffffffff819df1e7: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c5090)
Location: net/socket.c:669
Inline: False
Direct callers:
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_send
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff819c5090-ffffffff819c50f7: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a745c0)
Location: net/socket.c:719
Inline: False
Direct callers:
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_send
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81a745c0-ffffffff81a74627: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be7350)
Location: net/socket.c:729
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_send
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81be7350-ffffffff81be73bf: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d93410)
Location: net/socket.c:731
Inline: False
Direct callers:
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81d93410-ffffffff81d9347f: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e026d5)
Location: net/socket.c:746
Inline: True
Inline callers:
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
Direct callers:
  - fs/splice.c:splice_to_socket
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
  - io_uring/net.c:io_send
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81e020d0-ffffffff81e0219e: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebf040)
Location: net/socket.c:756
Inline: False
Direct callers:
  - fs/splice.c:splice_to_socket
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send
  - io_uring/net.c:io_send
  - net/socket.c:kernel_sendmsg
  - net/core/skbuff.c:__skb_send_sock
  - net/core/skbuff.c:__skb_send_sock
  - net/handshake/alert.c:tls_alert_send
```
**Symbols:**

```
ffffffff81ebf040-ffffffff81ebf184: sock_sendmsg (STB_GLOBAL)
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
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba2408)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffff800010ba2408-ffff800010ba2468: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc42e0)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
c0cc42e0-c0cc4334: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c77260)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
c000000000c77260-c000000000c7730c: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073a488)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffe00073a488-ffffffe00073a4d6: sock_sendmsg (STB_GLOBAL)
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
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818adea0)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff818adea0-ffffffff818adf07: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81867df0)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff81867df0-ffffffff81867e57: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818feea0)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff818feea0-ffffffff818fef07: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_sendmsg(struct socket *sock, struct msghdr *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191fe90)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/socket.c:____sys_sendmsg
  - net/socket.c:____sys_sendmsg
  - net/socket.c:__sys_sendto
  - net/socket.c:sock_write_iter
  - net/socket.c:kernel_sendmsg
```
**Symbols:**

```
ffffffff8191fe90-ffffffff8191fef7: sock_sendmsg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
