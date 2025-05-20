# Function: <code>sock_recvmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fdb30)
Location: net/socket.c:716
Inline: True
Direct callers:
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
  - net/socket.c:SYSC_recvfrom
```
**Symbols:**

```
ffffffff816fdb30-ffffffff816fdb74: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764660)
Location: net/socket.c:714
Inline: True
Direct callers:
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff81764660-ffffffff817646a4: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817916e0)
Location: net/socket.c:745
Inline: True
Direct callers:
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff817916e0-ffffffff81791724: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae300)
Location: net/socket.c:795
Inline: False
Direct callers:
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff817ae300-ffffffff817ae344: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818263d0)
Location: net/socket.c:814
Inline: False
Direct callers:
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff818263d0-ffffffff8182641a: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81870910)
Location: net/socket.c:818
Inline: True
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff81870910-ffffffff8187095a: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81891420)
Location: net/socket.c:798
Inline: True
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff81891420-ffffffff8189146a: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dc130)
Location: net/socket.c:885
Inline: False
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff818dc130-ffffffff818dc1a2: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190ed10)
Location: net/socket.c:885
Inline: False
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff8190ed10-ffffffff8190ed82: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df610)
Location: net/socket.c:900
Inline: False
Direct callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recv
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff819df610-ffffffff819df682: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dee20)
Location: net/socket.c:900
Inline: False
Direct callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recv
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff819dee20-ffffffff819dee92: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4d30)
Location: net/socket.c:902
Inline: False
Direct callers:
  - fs/io_uring.c:io_recv
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff819c4d30-ffffffff819c4da2: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a74260)
Location: net/socket.c:961
Inline: False
Direct callers:
  - fs/io_uring.c:io_recv
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff81a74260-ffffffff81a742d2: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be6fa0)
Location: net/socket.c:1009
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_recv
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff81be6fa0-ffffffff81be7027: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d93020)
Location: net/socket.c:1014
Inline: False
Direct callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff81d93020-ffffffff81d930a7: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e01fca)
Location: net/socket.c:1042
Inline: True
Inline callers:
  - net/socket.c:kernel_recvmsg
Direct callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
```
**Symbols:**

```
ffffffff81e01b50-ffffffff81e01c33: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebe98a)
Location: net/socket.c:1064
Inline: True
Inline callers:
  - net/socket.c:kernel_recvmsg
Direct callers:
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_recvmsg
  - net/socket.c:____sys_recvmsg
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
```
**Symbols:**

```
ffffffff81ebe510-ffffffff81ebe5f3: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba21b0)
Location: net/socket.c:885
Inline: True
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffff800010ba21b0-ffff800010ba2218: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc4088)
Location: net/socket.c:885
Inline: True
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
c0cc4088-c0cc40dc: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76f00)
Location: net/socket.c:885
Inline: True
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
c000000000c76f00-c000000000c76f88: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073a23a)
Location: net/socket.c:885
Inline: True
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffe00073a23a-ffffffe00073a288: sock_recvmsg (STB_GLOBAL)
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
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818aed10)
Location: net/socket.c:885
Inline: False
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff818aed10-ffffffff818aed82: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81868c60)
Location: net/socket.c:885
Inline: False
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff81868c60-ffffffff81868cd2: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ffd10)
Location: net/socket.c:885
Inline: False
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff818ffd10-ffffffff818ffd82: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_recvmsg(struct socket *sock, struct msghdr *msg, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81920d00)
Location: net/socket.c:885
Inline: False
Direct callers:
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:sock_read_iter
  - net/socket.c:kernel_recvmsg
```
**Symbols:**

```
ffffffff81920d00-ffffffff81920d72: sock_recvmsg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param reordered. </b>
<code>sock, msg, size, flags</code> ➡️ <code>sock, msg, flags</code>
</li>
</ul>
</details>
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
