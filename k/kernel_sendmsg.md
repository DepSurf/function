# Function: <code>kernel_sendmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fe1a0)
Location: net/socket.c:625
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff816fe1a0-ffffffff816fe1d0: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764b90)
Location: net/socket.c:623
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff81764b90-ffffffff81764bc0: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81791c10)
Location: net/socket.c:649
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff81791c10-ffffffff81791c40: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b0150)
Location: net/socket.c:647
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff817b0150-ffffffff817b0180: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818282d0)
Location: net/socket.c:652
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff818282d0-ffffffff81828300: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818710d0)
Location: net/socket.c:656
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff818710d0-ffffffff81871100: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818922e0)
Location: net/socket.c:636
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff818922e0-ffffffff81892310: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dc460)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff818dc460-ffffffff818dc492: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190e000)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff8190e000-ffffffff8190e032: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dfb20)
Location: net/socket.c:688
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff819dfb20-ffffffff819dfb52: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df2e0)
Location: net/socket.c:688
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff819df2e0-ffffffff819df312: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c51f0)
Location: net/socket.c:690
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff819c51f0-ffffffff819c5222: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a74720)
Location: net/socket.c:740
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81a74720-ffffffff81a74752: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be74c0)
Location: net/socket.c:750
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81be74c0-ffffffff81be74ff: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d935a0)
Location: net/socket.c:752
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
  - net/core/skbuff.c:__skb_send_sock
```
**Symbols:**

```
ffffffff81d935a0-ffffffff81d935df: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e02530)
Location: net/socket.c:767
Inline: False
```
**Symbols:**

```
ffffffff81e02530-ffffffff81e02627: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebf1a0)
Location: net/socket.c:788
Inline: False
```
**Symbols:**

```
ffffffff81ebf1a0-ffffffff81ebf1df: kernel_sendmsg (STB_GLOBAL)
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
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba2558)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffff800010ba2558-ffff800010ba25c0: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc4438)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
c0cc4438-c0cc4480: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c77460)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
c000000000c77460-c000000000c774bc: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073a5a2)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffe00073a5a2-ffffffe00073a5fa: kernel_sendmsg (STB_GLOBAL)
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
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ae000)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff818ae000-ffffffff818ae032: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81867f50)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff81867f50-ffffffff81867f82: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ff000)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff818ff000-ffffffff818ff032: kernel_sendmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_sendmsg(struct socket *sock, struct msghdr *msg, struct kvec *vec, size_t num, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191fff0)
Location: net/socket.c:673
Inline: False
Direct callers:
  - net/core/sock.c:sock_no_sendpage
```
**Symbols:**

```
ffffffff8191fff0-ffffffff81920022: kernel_sendmsg (STB_GLOBAL)
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
