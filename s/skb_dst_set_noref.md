# Function: <code>skb_dst_set_noref</code>

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
In net/ipv4/route.c (ffffffff81755ea3)
Location: include/linux/skbuff.h:777
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8175e66b)
Location: include/linux/skbuff.h:777
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177e300)
Location: include/linux/skbuff.h:777
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8178aabc)
Location: include/linux/skbuff.h:777
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f055c)
Location: include/linux/skbuff.h:777
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff817f7729)
Location: include/linux/skbuff.h:777
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff817c2074)
Location: include/linux/skbuff.h:865
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff817ca8d0)
Location: include/linux/skbuff.h:865
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb750)
Location: include/linux/skbuff.h:865
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff817f8147)
Location: include/linux/skbuff.h:865
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f3c2)
Location: include/linux/skbuff.h:865
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81866879)
Location: include/linux/skbuff.h:865
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff817f261c)
Location: include/linux/skbuff.h:879
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/ip_output.c (ffffffff817fa544)
Location: include/linux/skbuff.h:879
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181c0c0)
Location: include/linux/skbuff.h:879
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81828fe7)
Location: include/linux/skbuff.h:879
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818913e2)
Location: include/linux/skbuff.h:879
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81898f79)
Location: include/linux/skbuff.h:879
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff81811dfa)
Location: include/linux/skbuff.h:832
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8181a940)
Location: include/linux/skbuff.h:832
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c8a3)
Location: include/linux/skbuff.h:832
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8184a340)
Location: include/linux/skbuff.h:832
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff818aa31b)
Location: include/linux/skbuff.h:832
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b79e0)
Location: include/linux/skbuff.h:832
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff818bf119)
Location: include/linux/skbuff.h:832
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff8189141c)
Location: include/linux/skbuff.h:912
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81899920)
Location: include/linux/skbuff.h:912
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbfe2)
Location: include/linux/skbuff.h:912
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff818c9ef0)
Location: include/linux/skbuff.h:912
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff8192cddb)
Location: include/linux/skbuff.h:912
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193a83c)
Location: include/linux/skbuff.h:912
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81942259)
Location: include/linux/skbuff.h:912
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff818e5410)
Location: include/linux/skbuff.h:916
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffff818edd58)
Location: include/linux/skbuff.h:916
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819119bf)
Location: include/linux/skbuff.h:916
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8191fea2)
Location: include/linux/skbuff.h:916
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff81985538)
Location: include/linux/skbuff.h:916
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8199370e)
Location: include/linux/skbuff.h:916
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff8199b07c)
Location: include/linux/skbuff.h:916
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff81912326)
Location: include/linux/skbuff.h:940
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffff8191b51b)
Location: include/linux/skbuff.h:940
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819401a9)
Location: include/linux/skbuff.h:940
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8194eb00)
Location: include/linux/skbuff.h:940
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/udp.c (ffffffff819bbca8)
Location: include/linux/skbuff.h:940
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9ad8)
Location: include/linux/skbuff.h:940
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d19dc)
Location: include/linux/skbuff.h:940
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff819749ad)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffff8197d7f7)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a46bd)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff819b32db)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81a1a32d)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a2a93c)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38570)
Location: include/linux/skbuff.h:960
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a4081c)
Location: include/linux/skbuff.h:960
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff819ab3c9)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffff819b4197)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db3bd)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff819ea05e)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81a50f9d)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a6148f)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f0c0)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a77401)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff81a9555e)
Location: include/linux/skbuff.h:988
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_output.c (ffffffff81a9e2d2)
Location: include/linux/skbuff.h:988
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac844d)
Location: include/linux/skbuff.h:988
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81ad7c85)
Location: include/linux/skbuff.h:988
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81b4863b)
Location: include/linux/skbuff.h:988
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b5a770)
Location: include/linux/skbuff.h:988
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67245)
Location: include/linux/skbuff.h:988
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b71691)
Location: include/linux/skbuff.h:988
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/sched/sch_frag.c (ffffffff81a6f7b5)
Location: include/linux/skbuff.h:995
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81a9f682)
Location: include/linux/skbuff.h:995
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_output.c (ffffffff81aa81c6)
Location: include/linux/skbuff.h:995
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad43ed)
Location: include/linux/skbuff.h:995
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81ae42d5)
Location: include/linux/skbuff.h:995
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81b5721b)
Location: include/linux/skbuff.h:995
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b68e70)
Location: include/linux/skbuff.h:995
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b757cd)
Location: include/linux/skbuff.h:995
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b80321)
Location: include/linux/skbuff.h:995
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/sched/sch_frag.c (ffffffff81a580a6)
Location: include/linux/skbuff.h:1001
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81a8a5c2)
Location: include/linux/skbuff.h:1001
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_output.c (ffffffff81a93182)
Location: include/linux/skbuff.h:1001
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf48a)
Location: include/linux/skbuff.h:1001
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81acf49b)
Location: include/linux/skbuff.h:1001
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81b44e18)
Location: include/linux/skbuff.h:1001
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81b56fac)
Location: include/linux/skbuff.h:1001
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b641fc)
Location: include/linux/skbuff.h:1001
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81b6ef21)
Location: include/linux/skbuff.h:1001
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/sched/sch_frag.c (ffffffff81b11075)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81b45466)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_output.c (ffffffff81b4e589)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7cfd7)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81b8debb)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81c0bf2c)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81c1d1b4)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2c890)
Location: include/linux/skbuff.h:1012
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81c36fbf)
Location: include/linux/skbuff.h:1012
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/sched/sch_frag.c (ffffffff81c98049)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81cd215d)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_output.c (ffffffff81cdbea0)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0cf17)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81d1f104)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81da6dc5)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81dbbd34)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcd720)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81dd4bd6)
Location: include/linux/skbuff.h:1302
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/sched/sch_frag.c (ffffffff81e53ff9)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81e92686)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_output.c (ffffffff81e9c8a0)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2996)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81ee621c)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81f76380)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81f8be5c)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9e838)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81fa6286)
Location: include/linux/skbuff.h:1144
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/sched/sch_frag.c (ffffffff81eaf879)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81ef0e1d)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_output.c (ffffffff81efb4b4)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31672)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81f45a14)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81fd6416)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81fec5f4)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81fff2f4)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff82006b06)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/sched/sch_frag.c (ffffffff81f722f3)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/ipv4/route.c (ffffffff81fb4f70)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
```
In net/ipv4/ip_output.c (ffffffff81fbf3b7)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff7862)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8200bb64)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff820a3da4)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff820ba204)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ce004)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_early_demux
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff820d5966)
Location: include/linux/skbuff.h:1161
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffff800010c5b564)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffff800010c6483c)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e798)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffff800010c9f84c)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffff800010d14f2c)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffff800010d24664)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d36ae8)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffff800010d40a6c)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (c0d6ab80)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (c0d744b8)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (c0d9d6f8)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (c0dacb78)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (c0e1aba4)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (c0e2b504)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (c0e3a7bc)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (c0e434d8)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (c000000000d5d478)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (c000000000d68b08)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d170)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (c000000000db2370)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (c000000000e41dcc)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (c000000000e56f4c)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6a320)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (c000000000e75110)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffe0007c485a)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffe0007cc1d0)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eead4)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffe0007fc382)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffe00085a67a)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffe000868208)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008752e2)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffe00087c2fe)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff8194b239)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffff81954007)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b22d)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff81989ece)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff819f062d)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a00b1f)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0e750)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a16a91)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff81904d29)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffff8190daf7)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81934ced)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff8194398e)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff819ad3ed)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff819bd8df)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb510)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff819d3851)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff819b5a09)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffff819be7d7)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e59fd)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff819f469e)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81a5b0ad)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a6b59f)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a791d0)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a81511)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
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
In net/ipv4/route.c (ffffffff819bf1d4)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/ip_output.c (ffffffff819c8119)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_queue_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef6bd)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_early_demux
```
```
In net/ipv4/udp.c (ffffffff819fe85e)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
```
```
In net/ipv6/route.c (ffffffff81a6738d)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
```
```
In net/ipv6/udp.c (ffffffff81a77baf)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a85990)
Location: include/linux/skbuff.h:956
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (ffffffff81a8de06)
Location: include/linux/skbuff.h:956
Inline: True
Inline callers:
  - net/ipv6/inet6_connection_sock.c:inet6_csk_xmit
```
</details>
</li>
</ul>

## Differences
