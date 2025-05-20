# Function: <code>kernel_bind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fb730)
Location: net/socket.c:3169
Inline: False
```
**Symbols:**

```
ffffffff816fb730-ffffffff816fb742: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762190)
Location: net/socket.c:3171
Inline: False
```
**Symbols:**

```
ffffffff81762190-ffffffff817621a2: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178f1c0)
Location: net/socket.c:3219
Inline: False
```
**Symbols:**

```
ffffffff8178f1c0-ffffffff8178f1d2: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ad1c0)
Location: net/socket.c:3269
Inline: False
```
**Symbols:**

```
ffffffff817ad1c0-ffffffff817ad1d2: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818251d0)
Location: net/socket.c:3271
Inline: False
```
**Symbols:**

```
ffffffff818251d0-ffffffff818251e8: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186f200)
Location: net/socket.c:3237
Inline: False
```
**Symbols:**

```
ffffffff8186f200-ffffffff8186f218: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8188f680)
Location: net/socket.c:3303
Inline: False
```
**Symbols:**

```
ffffffff8188f680-ffffffff8188f698: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818d96e0)
Location: net/socket.c:3496
Inline: False
```
**Symbols:**

```
ffffffff818d96e0-ffffffff818d96f8: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190b6e0)
Location: net/socket.c:3577
Inline: False
```
**Symbols:**

```
ffffffff8190b6e0-ffffffff8190b6f8: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd8b0)
Location: net/socket.c:3521
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff819dd8b0-ffffffff819dd8c8: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd2a0)
Location: net/socket.c:3513
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff819dd2a0-ffffffff819dd2b8: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c34f0)
Location: net/socket.c:3499
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff819c34f0-ffffffff819c3508: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a72da0)
Location: net/socket.c:3384
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81a72da0-ffffffff81a72db8: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be55c0)
Location: net/socket.c:3444
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81be55c0-ffffffff81be55e2: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91840)
Location: net/socket.c:3432
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81d91840-ffffffff81d91862: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81dffb60)
Location: net/socket.c:3473
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81dffb60-ffffffff81dffb82: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc630)
Location: net/socket.c:3543
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81ebc630-ffffffff81ebc6d2: kernel_bind (STB_GLOBAL)
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
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba0b10)
Location: net/socket.c:3577
Inline: False
```
**Symbols:**

```
ffff800010ba0b10-ffff800010ba0b5c: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc2f64)
Location: net/socket.c:3577
Inline: False
```
**Symbols:**

```
c0cc2f64-c0cc2f88: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c74a60)
Location: net/socket.c:3577
Inline: False
```
**Symbols:**

```
c000000000c74a60-c000000000c74aa4: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000738920)
Location: net/socket.c:3577
Inline: False
```
**Symbols:**

```
ffffffe000738920-ffffffe000738958: kernel_bind (STB_GLOBAL)
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
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ab6e0)
Location: net/socket.c:3577
Inline: False
```
**Symbols:**

```
ffffffff818ab6e0-ffffffff818ab6f8: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81865630)
Location: net/socket.c:3577
Inline: False
Direct callers:
  - net/ipv4/udp_tunnel.c:udp_sock_create4
  - net/ipv6/ip6_udp_tunnel.c:udp_sock_create6
```
**Symbols:**

```
ffffffff81865630-ffffffff81865648: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fc6e0)
Location: net/socket.c:3577
Inline: False
```
**Symbols:**

```
ffffffff818fc6e0-ffffffff818fc6f8: kernel_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_bind(struct socket *sock, struct sockaddr *addr, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191d6e0)
Location: net/socket.c:3577
Inline: False
```
**Symbols:**

```
ffffffff8191d6e0-ffffffff8191d6f8: kernel_bind (STB_GLOBAL)
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
