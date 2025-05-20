# Function: <code>sock_recv_timestamp</code>

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
In net/socket.c (ffffffff816fe1fa)
Location: include/net/sock.h:2138
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff817010d1)
Location: include/net/sock.h:2138
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81761bfb)
Location: include/net/sock.h:2138
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff817a3456)
Location: include/net/sock.h:2138
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff817f4ea4)
Location: include/net/sock.h:2138
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff81764bea)
Location: include/net/sock.h:2118
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff81767c51)
Location: include/net/sock.h:2118
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff817cdef8)
Location: include/net/sock.h:2118
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff818104b6)
Location: include/net/sock.h:2118
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81863f54)
Location: include/net/sock.h:2118
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff81791c6a)
Location: include/net/sock.h:2185
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff81794c71)
Location: include/net/sock.h:2185
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff817fdc58)
Location: include/net/sock.h:2185
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff818419b6)
Location: include/net/sock.h:2185
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81896604)
Location: include/net/sock.h:2185
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff817af24a)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff817b2e5e)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff8181e090)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81863095)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff818bcb84)
Location: include/net/sock.h:2209
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff8182738a)
Location: include/net/sock.h:2223
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff8182b14e)
Location: include/net/sock.h:2223
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff8189cfa0)
Location: include/net/sock.h:2223
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff818e31c5)
Location: include/net/sock.h:2223
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff8193fca4)
Location: include/net/sock.h:2223
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff818707fa)
Location: include/net/sock.h:2230
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff818751ce)
Location: include/net/sock.h:2230
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff818f146a)
Location: include/net/sock.h:2230
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81939bd6)
Location: include/net/sock.h:2230
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81998ae4)
Location: include/net/sock.h:2230
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff8189130a)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff81895a9b)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191efc7)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81969863)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819cf431)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff818daffa)
Location: include/net/sock.h:2350
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff818dffbd)
Location: include/net/sock.h:2350
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81981906)
Location: include/net/sock.h:2350
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff819d04b0)
Location: include/net/sock.h:2350
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a3e17e)
Location: include/net/sock.h:2350
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff8190d14a)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff8191216d)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b8146)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81a07000)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a74dee)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (0)
Location: include/net/sock.h:2423
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819e4c7d)
Location: include/net/sock.h:2423
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa2a66)
Location: include/net/sock.h:2423
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81af7600)
Location: include/net/sock.h:2423
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6f03e)
Location: include/net/sock.h:2423
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (0)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819e453d)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aacd76)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81b044e0)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b7db6e)
Location: include/net/sock.h:2444
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff819c6095)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff819ca5dd)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a97fc6)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81aef4f0)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81b6c75e)
Location: include/net/sock.h:2480
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff81a74ce5)
Location: include/net/sock.h:2539
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff81a79b7d)
Location: include/net/sock.h:2539
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b53456)
Location: include/net/sock.h:2539
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81bb0a70)
Location: include/net/sock.h:2539
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81c3464d)
Location: include/net/sock.h:2539
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff81be79a5)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81bec91f)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdfb7a)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81d44007)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81dd1f99)
Location: include/net/sock.h:2662
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff81d93e65)
Location: include/net/sock.h:2708
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81d9b3af)
Location: include/net/sock.h:2708
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9ff2b)
Location: include/net/sock.h:2708
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81f0d4d7)
Location: include/net/sock.h:2708
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81fa33f9)
Location: include/net/sock.h:2708
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff81e01a05)
Location: include/net/sock.h:2696
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81e0977f)
Location: include/net/sock.h:2696
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efe77b)
Location: include/net/sock.h:2696
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81f6d137)
Location: include/net/sock.h:2696
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff82003ca5)
Location: include/net/sock.h:2696
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff81ebe3c7)
Location: include/net/sock.h:2686
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_cmsgs
```
```
In net/core/sock.c (ffffffff81ec616f)
Location: include/net/sock.h:2686
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc299b)
Location: include/net/sock.h:2686
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff820338a7)
Location: include/net/sock.h:2686
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff820d2a55)
Location: include/net/sock.h:2686
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffff800010ba20ac)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffff800010ba9be4)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffff800010c694f4)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffff800010cbff68)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffff800010d3d838)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (c0cc483c)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c0cc82a8)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (c0d786cc)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (c0dcc3f0)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (c0e409f8)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (c000000000c76db4)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (c000000000c7f330)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (c000000000d6e134)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (c000000000ddb2c0)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (c000000000e71c50)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffe00073a16a)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffe00073d16c)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cf3d0)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffe0008169f8)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffe000879f50)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff818ad14a)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff818b216d)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81957fb6)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff819a6da0)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a1447e)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff8186709a)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff8186c0bd)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff81911aa6)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81960860)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff819d123e)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff818fe14a)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff8190316d)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c2786)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81a11640)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a7eefe)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
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
In net/socket.c (ffffffff8191f1da)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/socket.c:__sock_recv_ts_and_drops
```
```
In net/core/sock.c (ffffffff8192414d)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/core/sock.c:sock_recv_errqueue
```
```
In net/ipv4/ip_sockglue.c (ffffffff819cc186)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
```
```
In net/ipv4/ping.c (ffffffff81a1bfb0)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_recvmsg
```
```
In net/ipv6/datagram.c (ffffffff81a8b7be)
Location: include/net/sock.h:2371
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_rxpmtu
  - net/ipv6/datagram.c:ipv6_recv_error
  - net/ipv6/datagram.c:ipv6_recv_error
```
</details>
</li>
</ul>

## Differences
