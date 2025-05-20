# Function: <code>sk_can_busy_loop</code>

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
In net/socket.c (ffffffff816fdf66)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8170ca3c)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81766e70)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763504)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff817742bb)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff817d3370)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790566)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff817a15e2)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff818030e0)
Location: include/net/busy_poll.h:61
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In net/socket.c (ffffffff817adb34)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff817c0731)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81823c02)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81845c33)
Location: include/net/busy_poll.h:49
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
In net/socket.c (ffffffff81825ae4)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8183a17a)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff818a564a)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff818c56a9)
Location: include/net/busy_poll.h:49
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
In net/socket.c (ffffffff818706ec)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/socket.c:sock_poll
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81884901)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff818f6de2)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8191d104)
Location: include/net/busy_poll.h:49
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
In net/socket.c (ffffffff818901eb)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff818a4b61)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81925452)
Location: include/net/busy_poll.h:49
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff8194b6b4)
Location: include/net/busy_poll.h:49
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
In net/socket.c (ffffffff818da066)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff818f0300)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81989125)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819afdd3)
Location: include/net/busy_poll.h:37
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
In net/socket.c (ffffffff8190c046)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819222e0)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff819c0585)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819e6a69)
Location: include/net/busy_poll.h:37
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
In net/socket.c (ffffffff819defd8)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819f5cf9)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81aab0d5)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ad41fb)
Location: include/net/busy_poll.h:37
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
In net/socket.c (ffffffff819de86c)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819f57bf)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81ab6a24)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ae073b)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81bb6753)
Location: include/net/busy_poll.h:39
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
In net/socket.c (ffffffff819c480c)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819db95f)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81aa1bea)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81acc727)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81ba5713)
Location: include/net/busy_poll.h:39
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
In net/socket.c (ffffffff81a73c6c)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81a8bbaf)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81b5e6fa)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81b8afb7)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81c73298)
Location: include/net/busy_poll.h:39
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
In net/socket.c (ffffffff81be6ede)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81c013f2)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81ced0d4)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81d1addb)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81e16fc8)
Location: include/net/busy_poll.h:39
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
In net/socket.c (ffffffff81d92ebe)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81db0742)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81eb1004)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81ee237b)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff81feebba)
Location: include/net/busy_poll.h:39
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
In net/socket.c (ffffffff81e012c0)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81e20c02)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81f0f694)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81f41e7b)
Location: include/net/busy_poll.h:39
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff8206b59e)
Location: include/net/busy_poll.h:39
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
In net/socket.c (ffffffff81ebdc70)
Location: include/net/busy_poll.h:40
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81edead2)
Location: include/net/busy_poll.h:40
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81fd3884)
Location: include/net/busy_poll.h:40
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff82007d0b)
Location: include/net/busy_poll.h:40
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
```
In net/xdp/xsk.c (ffffffff8213dfea)
Location: include/net/busy_poll.h:40
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
In net/socket.c (ffff800010ba1104)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffff800010bbcd80)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffff800010c70a7c)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffff800010c99e84)
Location: include/net/busy_poll.h:37
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
In net/socket.c (c0cc3470)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (c0cd8f7c)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (c0d7faa0)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (c0daa490)
Location: include/net/busy_poll.h:37
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
In net/socket.c (c000000000c75518)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (c000000000c95eb0)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (c000000000d77ac8)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (c000000000dab504)
Location: include/net/busy_poll.h:37
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
In net/socket.c (ffffffe000739198)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffe00074b504)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffe0007d62e4)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffe0007f8f40)
Location: include/net/busy_poll.h:37
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
In net/socket.c (ffffffff818ac046)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff818c22e0)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff819603f5)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819868d9)
Location: include/net/busy_poll.h:37
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
In net/socket.c (ffffffff81865f96)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff8187c220)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff81919ee5)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff81940399)
Location: include/net/busy_poll.h:37
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
In net/socket.c (ffffffff818fd046)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff819132e0)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff819cabc5)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819f10a9)
Location: include/net/busy_poll.h:37
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
In net/socket.c (ffffffff8191e0b6)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/socket.c:sock_poll
```
```
In net/core/datagram.c (ffffffff81934460)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_try_recv_datagram
```
```
In net/ipv4/tcp.c (ffffffff819d4755)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
```
In net/ipv4/udp.c (ffffffff819f948b)
Location: include/net/busy_poll.h:37
Inline: True
Inline callers:
  - net/ipv4/udp.c:__skb_recv_udp
```
</details>
</li>
</ul>

## Differences
