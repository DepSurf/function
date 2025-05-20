# Function: <code>sk_mem_pages</code>

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
In net/core/sock.c (ffffffff81702a05)
Location: include/net/sock.h:1371
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp_output.c (ffffffff81778f40)
Location: include/net/sock.h:1371
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81768068)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp_output.c (ffffffff817e60ff)
Location: include/net/sock.h:1278
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
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
In net/core/sock.c (ffffffff81795206)
Location: include/net/sock.h:1334
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8181681f)
Location: include/net/sock.h:1334
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81824dc7)
Location: include/net/sock.h:1334
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff817b3916)
Location: include/net/sock.h:1337
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81836b1f)
Location: include/net/sock.h:1337
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff8184827e)
Location: include/net/sock.h:1337
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff8182bd46)
Location: include/net/sock.h:1341
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff818b61cf)
Location: include/net/sock.h:1341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff818c7ce3)
Location: include/net/sock.h:1341
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff81875885)
Location: include/net/sock.h:1356
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8190ba0f)
Location: include/net/sock.h:1356
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff8191dfb7)
Location: include/net/sock.h:1356
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff818961c5)
Location: include/net/sock.h:1394
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff81939cdf)
Location: include/net/sock.h:1394
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff8194cc07)
Location: include/net/sock.h:1394
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff818e06c5)
Location: include/net/sock.h:1397
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp_output.c (ffffffff8199df9f)
Location: include/net/sock.h:1397
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff819b13cb)
Location: include/net/sock.h:1397
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff81912895)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bc581)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff819d4a5f)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff819e8118)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff819e44e1)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa6feb)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1430)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81ad5f33)
Location: include/net/sock.h:1455
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff819e3d68)
Location: include/net/sock.h:1471
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab167b)
Location: include/net/sock.h:1471
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff81accea0)
Location: include/net/sock.h:1471
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81ae2513)
Location: include/net/sock.h:1471
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff819c9df8)
Location: include/net/sock.h:1487
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c0bf)
Location: include/net/sock.h:1487
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8070)
Location: include/net/sock.h:1487
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81acd433)
Location: include/net/sock.h:1487
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81bacb82)
Location: include/net/sock.h:1487
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff81a791f9)
Location: include/net/sock.h:1497
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b5795f)
Location: include/net/sock.h:1497
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff81b75230)
Location: include/net/sock.h:1497
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81b8bdf3)
Location: include/net/sock.h:1497
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81c79527)
Location: include/net/sock.h:1497
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff81bed711)
Location: include/net/sock.h:1570
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5945)
Location: include/net/sock.h:1570
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff81d04a45)
Location: include/net/sock.h:1570
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81d18bdd)
Location: include/net/sock.h:1570
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81e1e3c6)
Location: include/net/sock.h:1570
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff81d9dc56)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8b45)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9a4c)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81ee1968)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/mptcp/protocol.c (ffffffff81ff6e0b)
Location: include/net/sock.h:1616
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff81e0c4d8)
Location: include/net/sock.h:1607
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f073da)
Location: include/net/sock.h:1607
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff81f2859c)
Location: include/net/sock.h:1607
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/mptcp/protocol.c (ffffffff820734ed)
Location: include/net/sock.h:1607
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffffffff81ec8e8c)
Location: include/net/sock.h:1582
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:__sock_queue_rcv_skb
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb71f)
Location: include/net/sock.h:1582
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff81fed02c)
Location: include/net/sock.h:1582
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/mptcp/protocol.c (ffffffff8214773d)
Location: include/net/sock.h:1582
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
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
In net/core/sock.c (ffff800010bacf04)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6dfac)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffff800010c87694)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffff800010c9c6ec)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (c0cc8ab8)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (c0d7cc0c)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (c0d969d0)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (c0da77e4)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (c000000000c7fe04)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (c000000000d7471c)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (c000000000d941bc)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (c000000000daec20)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffe00073d7da)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d361e)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8a3a)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffe0007fa6e4)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff818b2895)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195c3f1)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff819748cf)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81987f88)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff8186c7e5)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915ee1)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff8192e38f)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff81941a48)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff81903895)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6bc1)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff819df09f)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff819f2758)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In net/core/sock.c (ffffffff81924895)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819d0711)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp_output.c (ffffffff819e8d3f)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/udp.c (ffffffff819fc5a4)
Location: include/net/sock.h:1407
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
</details>
</li>
</ul>

## Differences
