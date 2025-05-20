# Function: <code>sk_busy_loop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fdfc8)
Location: include/net/busy_poll.h:78
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8170cc48)
Location: include/net/busy_poll.h:78
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81767606)
Location: include/net/busy_poll.h:78
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool sk_busy_loop(struct sock *sk, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81783350)
Location: net/core/dev.c:4967
Inline: False
Direct callers:
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff81783350-ffffffff817836a4: sk_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool sk_busy_loop(struct sock *sk, int nonblock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aec20)
Location: net/core/dev.c:5081
Inline: False
Direct callers:
  - net/socket.c:sock_poll
  - net/core/datagram.c:__skb_try_recv_datagram
  - net/ipv4/tcp.c:tcp_recvmsg
```
**Symbols:**

```
ffffffff817aec20-ffffffff817aeef8: sk_busy_loop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817adb60)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff817c0762)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff818242be)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81845c7f)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825b10)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8183a18a)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff818a5c47)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff818c56bd)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81870757)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8188494a)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff818f7367)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8191d16e)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890230)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff818a4baa)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff819259ce)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8194b71e)
Location: include/net/busy_poll.h:114
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818da08b)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff818f0297)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81989730)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819afcb5)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190c06b)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81922277)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff819c0ba5)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819e6945)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df01a)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819f5d39)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81aab637)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ad426b)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819de8b7)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819f580e)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81ab6b18)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ae07b5)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81bb67ae)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c4857)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819db9ae)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81aa1cda)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81acc7a1)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81ba57bf)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a73cb7)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81a8bbfe)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81b5e7ea)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81b8b031)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81c7331a)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be6f3f)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81c0145a)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81ced1dc)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81d1ae33)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81e17092)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_recvmsg
  - net/xdp/xsk.c:xsk_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d92f1f)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81db07aa)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81eb1108)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ee23d3)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81feec49)
Location: include/net/busy_poll.h:104
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e01323)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81e20c6a)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81f0f798)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81f41ed3)
Location: include/net/busy_poll.h:104
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff8206b6c5)
Location: include/net/busy_poll.h:104
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebdcd3)
Location: include/net/busy_poll.h:105
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81edeb3a)
Location: include/net/busy_poll.h:105
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81fd3988)
Location: include/net/busy_poll.h:105
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff82007d63)
Location: include/net/busy_poll.h:105
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff8213e079)
Location: include/net/busy_poll.h:105
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba1124)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffff800010bbcd94)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffff800010c70f98)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffff800010c99e98)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc34ac)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (c0cd8ef8)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (c0d7ffb0)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (c0daa38c)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7553c)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (c000000000c95e2c)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (c000000000d781dc)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (c000000000dab3ec)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe0007391b6)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffe00074b500)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffe0007d676e)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffe0007f8f48)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ac06b)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff818c2277)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81960a15)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819867b5)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81865fbb)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8187c1b7)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff8191a505)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81940275)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fd06b)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81913277)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff819cb1e5)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819f0f85)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191e0db)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819343f7)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff819d4d75)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819f937b)
Location: include/net/busy_poll.h:102
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
