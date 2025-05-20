# Function: <code>sock_create_kern</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd360)
Location: net/socket.c:1207
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff816fd360-ffffffff816fd376: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763e90)
Location: net/socket.c:1200
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff81763e90-ffffffff81763ea6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790ec0)
Location: net/socket.c:1243
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff81790ec0-ffffffff81790ed6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae7e0)
Location: net/socket.c:1292
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff817ae7e0-ffffffff817ae7f6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818268b0)
Location: net/socket.c:1311
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff818268b0-ffffffff818268c6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186ffa0)
Location: net/socket.c:1333
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff8186ffa0-ffffffff8186ffb6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890b70)
Location: net/socket.c:1320
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff81890b70-ffffffff81890b86: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818daa80)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff818daa80-ffffffff818daa96: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190cbd0)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff8190cbd0-ffffffff8190cbe6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de940)
Location: net/socket.c:1495
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff819de940-ffffffff819de956: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de380)
Location: net/socket.c:1473
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff819de380-ffffffff819de396: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4390)
Location: net/socket.c:1464
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff819c4390-ffffffff819c43a6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a739f0)
Location: net/socket.c:1534
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81a739f0-ffffffff81a73a06: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be67c0)
Location: net/socket.c:1582
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81be67c0-ffffffff81be67e8: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d92c40)
Location: net/socket.c:1587
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81d92c40-ffffffff81d92c68: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e00fb0)
Location: net/socket.c:1616
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81e00fb0-ffffffff81e00fd8: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebd6b0)
Location: net/socket.c:1638
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket
```
**Symbols:**

```
ffffffff81ebd6b0-ffffffff81ebd6d8: sock_create_kern (STB_GLOBAL)
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
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1a90)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffff800010ba1a90-ffff800010ba1af0: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3b14)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
c0cc3b14-c0cc3b44: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76230)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
c000000000c76230-c000000000c76248: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe000739ba2)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffe000739ba2-ffffffe000739bee: sock_create_kern (STB_GLOBAL)
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
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818acbd0)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff818acbd0-ffffffff818acbe6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866b20)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
  - net/ipv4/udp_tunnel.c:udp_sock_create4
  - net/ipv6/ip6_udp_tunnel.c:udp_sock_create6
```
**Symbols:**

```
ffffffff81866b20-ffffffff81866b36: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fdbd0)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff818fdbd0-ffffffff818fdbe6: sock_create_kern (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_create_kern(struct net *net, int family, int type, int protocol, struct socket **res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191ec60)
Location: net/socket.c:1485
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_create
  - net/ipv4/af_inet.c:inet_ctl_sock_create
```
**Symbols:**

```
ffffffff8191ec60-ffffffff8191ec76: sock_create_kern (STB_GLOBAL)
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
