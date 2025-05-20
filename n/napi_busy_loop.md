# Function: <code>napi_busy_loop</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cd5d0)
Location: net/core/dev.c:5299
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff817cd5d0-ffffffff817cd83a: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846d00)
Location: net/core/dev.c:5440
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81846d00-ffffffff81846f6a: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890370)
Location: net/core/dev.c:5570
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81890370-ffffffff818905d0: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b0c20)
Location: net/core/dev.c:6123
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff818b0c20-ffffffff818b0e82: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fd9c0)
Location: net/core/dev.c:6133
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff818fd9c0-ffffffff818fdc1e: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81935730)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81935730-ffffffff819359a4: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0a3f0)
Location: net/core/dev.c:6458
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81a0a3f0-ffffffff81a0a686: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0c710)
Location: net/core/dev.c:6584
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81a0c710-ffffffff81a0c9ea: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f29f0)
Location: net/core/dev.c:6705
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff819f29f0-ffffffff819f2cca: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa48c0)
Location: net/core/dev.c:6691
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81aa48c0-ffffffff81aa4b9a: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1c020)
Location: net/core/dev.c:6177
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81c1c020-ffffffff81c1c35a: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcd000)
Location: net/core/dev.c:6166
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81dcd000-ffffffff81dcd33a: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3db60)
Location: net/core/dev.c:6143
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81e3db60-ffffffff81e3de93: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg, bool prefer_busy_poll, u16 budget);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efc400)
Location: net/core/dev.c:6225
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81efc400-ffffffff81efc733: napi_busy_loop (STB_GLOBAL)
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
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd3af0)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffff800010bd3af0-ffff800010bd3db8: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cee7e4)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
c0cee7e4-c0ceeb48: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb2830)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
c000000000cb2830-c000000000cb2bc4: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075dc0e)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:do_epoll_wait
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffe00075dc0e-ffffffe00075de76: napi_busy_loop (STB_GLOBAL)
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
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d5700)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff818d5700-ffffffff818d5974: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188f570)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff8188f570-ffffffff8188f7e4: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81926730)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81926730-ffffffff819269a4: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void napi_busy_loop(unsigned int napi_id, bool (*loop_end)(void *, long unsigned int), void *loop_end_arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81947d30)
Location: net/core/dev.c:6068
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_poll
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/udp.c:__skb_recv_udp
```
**Symbols:**

```
ffffffff81947d30-ffffffff81947fec: napi_busy_loop (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool prefer_busy_poll</code>
</li>
<li>
<b>Param added. </b>
<code>u16 budget</code>
</li>
</ul>
</details>
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
