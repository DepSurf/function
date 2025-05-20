# Function: <code>sock_no_sendpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700c00)
Location: net/core/sock.c:2260
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81700c00-ffffffff81700cb6: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767780)
Location: net/core/sock.c:2333
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81767780-ffffffff81767832: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794790)
Location: net/core/sock.c:2357
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81794790-ffffffff8179483c: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b29b0)
Location: net/core/sock.c:2517
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff817b29b0-ffffffff817b2a5c: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182abd0)
Location: net/core/sock.c:2560
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff8182abd0-ffffffff8182ac7c: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874cc0)
Location: net/core/sock.c:2635
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81874cc0-ffffffff81874d69: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895580)
Location: net/core/sock.c:2579
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81895580-ffffffff81895629: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818dfaa0)
Location: net/core/sock.c:2722
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff818dfaa0-ffffffff818dfb4c: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81911c50)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81911c50-ffffffff81911cfc: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4de0)
Location: net/core/sock.c:2866
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff819e4de0-ffffffff819e4e92: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e4660)
Location: net/core/sock.c:2838
Inline: False
Direct callers:
  - net/socket.c:sock_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff819e4660-ffffffff819e4712: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ca6e0)
Location: net/core/sock.c:2861
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff819ca6e0-ffffffff819ca792: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a79cb0)
Location: net/core/sock.c:2992
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81a79cb0-ffffffff81a79d62: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bed460)
Location: net/core/sock.c:3155
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81bed460-ffffffff81bed531: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d99ef0)
Location: net/core/sock.c:3235
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81d99ef0-ffffffff81d99fc7: sock_no_sendpage (STB_GLOBAL)
```
</details>
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
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010ba9700)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffff800010ba9700-ffff800010ba97c4: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc7ce0)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
c0cc7ce0-c0cc7d9c: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7ebf0)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
c000000000c7ebf0-c000000000c7ece4: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073cc9e)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffe00073cc9e-ffffffe00073cd44: sock_no_sendpage (STB_GLOBAL)
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
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b1c50)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff818b1c50-ffffffff818b1cfc: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186bba0)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff8186bba0-ffffffff8186bc4c: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81902c50)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81902c50-ffffffff81902cfc: sock_no_sendpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t sock_no_sendpage(struct socket *sock, struct page *page, int offset, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81923c00)
Location: net/core/sock.c:2737
Inline: False
Direct callers:
  - net/socket.c:kernel_sendpage
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/af_inet.c:inet_sendpage
```
**Symbols:**

```
ffffffff81923c00-ffffffff81923c86: sock_no_sendpage (STB_GLOBAL)
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
