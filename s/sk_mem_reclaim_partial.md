# Function: <code>sk_mem_reclaim_partial</code>

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
In net/core/datagram.c (ffffffff8170d059)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/core/datagram.c:skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
  - net/core/datagram.c:skb_kill_datagram
```
```
In net/ipv4/tcp.c (ffffffff81768eb2)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81779cbc)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/udp.c (ffffffff817888c2)
Location: include/net/sock.h:1408
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
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
In net/core/datagram.c (ffffffff8177548d)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff817d58fc)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6e8c)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/udp.c (ffffffff817f6212)
Location: include/net/sock.h:1315
Inline: True
Inline callers:
  - net/ipv4/udp.c:first_packet_length
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
In net/core/datagram.c (ffffffff817a2776)
Location: include/net/sock.h:1371
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff818058a8)
Location: include/net/sock.h:1371
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff818175cc)
Location: include/net/sock.h:1371
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff817c0293)
Location: include/net/sock.h:1374
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff81825d8a)
Location: include/net/sock.h:1374
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81837a6c)
Location: include/net/sock.h:1374
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff81839cb3)
Location: include/net/sock.h:1378
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff818a3e46)
Location: include/net/sock.h:1378
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff818b71ea)
Location: include/net/sock.h:1378
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff818843f3)
Location: include/net/sock.h:1393
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff818f9bc1)
Location: include/net/sock.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cb45)
Location: include/net/sock.h:1393
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff818a4873)
Location: include/net/sock.h:1431
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff81927aeb)
Location: include/net/sock.h:1431
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8193ae85)
Location: include/net/sock.h:1431
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff818efff4)
Location: include/net/sock.h:1434
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff8198a999)
Location: include/net/sock.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f1f5)
Location: include/net/sock.h:1434
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff81922014)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff819c115d)
Location: include/net/sock.h:1444
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5da5)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff819f5264)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff81aac88d)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2c65)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81bab305)
Location: include/net/sock.h:1492
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_clean_una
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
In net/core/datagram.c (ffffffff819f4c94)
Location: include/net/sock.h:1508
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff81ab41e0)
Location: include/net/sock.h:1508
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace6f5)
Location: include/net/sock.h:1508
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81bbea92)
Location: include/net/sock.h:1508
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In net/core/datagram.c (ffffffff819dae24)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff81a9f350)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9895)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81bafbbd)
Location: include/net/sock.h:1524
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In net/core/datagram.c (ffffffff81a8b4a4)
Location: include/net/sock.h:1534
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff81b5b100)
Location: include/net/sock.h:1534
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76cc5)
Location: include/net/sock.h:1534
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81c788cf)
Location: include/net/sock.h:1534
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In net/core/datagram.c (ffffffff81c01118)
Location: include/net/sock.h:1635
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff81ce9b54)
Location: include/net/sock.h:1635
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06555)
Location: include/net/sock.h:1635
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81e1b9db)
Location: include/net/sock.h:1635
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_mem_reclaim_partial
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbca1c)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffff800010c74078)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (ffff800010c88d18)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (c0cd8c88)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (c0d8277c)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (c0d97dfc)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (c000000000c95a44)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:__skb_free_datagram_locked
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (c000000000d7b050)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_timer.c (c000000000d95e18)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffe00074b2ca)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffe0007d7670)
Location: include/net/sock.h:1444
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9d36)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff818c2014)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff81960fcd)
Location: include/net/sock.h:1444
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff81975c15)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff8187bf54)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff8191aabd)
Location: include/net/sock.h:1444
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f6d5)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff81913014)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff819cb79d)
Location: include/net/sock.h:1444
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819e03e5)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/core/datagram.c (ffffffff81934194)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/core/datagram.c:skb_kill_datagram
  - net/core/datagram.c:skb_free_datagram
```
```
In net/ipv4/tcp.c (ffffffff819d532d)
Location: include/net/sock.h:1444
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea0a5)
Location: include/net/sock.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
</details>
</li>
</ul>

## Differences
