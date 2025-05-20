# Function: <code>gfp_any</code>

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
In net/netlink/af_netlink.c (ffffffff8174e4de)
Location: include/net/sock.h:2081
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81768026)
Location: include/net/sock.h:2081
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff817d9206)
Location: include/net/sock.h:2081
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
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
In net/netlink/af_netlink.c (ffffffff817ba67e)
Location: include/net/sock.h:2054
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff817d48e8)
Location: include/net/sock.h:2054
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff81847156)
Location: include/net/sock.h:2054
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
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
In net/netlink/af_netlink.c (ffffffff817ea01e)
Location: include/net/sock.h:2120
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81804628)
Location: include/net/sock.h:2120
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff81878f96)
Location: include/net/sock.h:2120
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
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
In net/netlink/af_netlink.c (ffffffff81809cee)
Location: include/net/sock.h:2144
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81824c28)
Location: include/net/sock.h:2144
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff8189e1d5)
Location: include/net/sock.h:2144
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff81888c4e)
Location: include/net/sock.h:2158
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff818a6a60)
Location: include/net/sock.h:2158
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff819207b5)
Location: include/net/sock.h:2158
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff818dc69e)
Location: include/net/sock.h:2165
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff818fbb5b)
Location: include/net/sock.h:2165
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff81978b05)
Location: include/net/sock.h:2165
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff8190907e)
Location: include/net/sock.h:2251
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81929ae4)
Location: include/net/sock.h:2251
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv6/route.c (ffffffff819ae785)
Location: include/net/sock.h:2251
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff8196a3d1)
Location: include/net/sock.h:2257
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff8198cce7)
Location: include/net/sock.h:2257
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff819d3bb4)
Location: include/net/sock.h:2257
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81a1d019)
Location: include/net/sock.h:2257
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff819a0e41)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819c3686)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81a0a724)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81a53ce9)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff81a7a651)
Location: include/net/sock.h:2328
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81aaed8a)
Location: include/net/sock.h:2328
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81afb9d4)
Location: include/net/sock.h:2328
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81b4b379)
Location: include/net/sock.h:2328
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In net/netlink/af_netlink.c (ffffffff81a834c1)
Location: include/net/sock.h:2349
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81ab8fe8)
Location: include/net/sock.h:2349
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81b090a4)
Location: include/net/sock.h:2349
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81b5a00a)
Location: include/net/sock.h:2349
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In net/netlink/af_netlink.c (ffffffff81a6c591)
Location: include/net/sock.h:2385
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81aa429b)
Location: include/net/sock.h:2385
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81af7234)
Location: include/net/sock.h:2385
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81b481ea)
Location: include/net/sock.h:2385
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In net/netlink/af_netlink.c (ffffffff81b25be1)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81b5ff51)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81bb6bd4)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81c0f4ba)
Location: include/net/sock.h:2439
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In net/netlink/af_netlink.c (ffffffff81cae799)
Location: include/net/sock.h:2562
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81ceed9e)
Location: include/net/sock.h:2562
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81d4a834)
Location: include/net/sock.h:2562
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81daa60a)
Location: include/net/sock.h:2562
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In net/netlink/af_netlink.c (ffffffff81e6bdd9)
Location: include/net/sock.h:2608
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81eb2028)
Location: include/net/sock.h:2608
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81f13ef4)
Location: include/net/sock.h:2608
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81f79dfa)
Location: include/net/sock.h:2608
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In net/netlink/af_netlink.c (ffffffff81ec7e39)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81f106d8)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81f73bc4)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81fda00a)
Location: include/net/sock.h:2596
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In net/netlink/af_netlink.c (ffffffff81f8b249)
Location: include/net/sock.h:2586
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff81fd48c4)
Location: include/net/sock.h:2586
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff8203a3b4)
Location: include/net/sock.h:2586
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff820a7a1a)
Location: include/net/sock.h:2586
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
  - net/ipv6/route.c:__ip6_del_rt_siblings
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
In net/netlink/af_netlink.c (ffff800010c4f554)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffff800010c76224)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffff800010cc3cf8)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffff800010d17e10)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (c0d5f6b0)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (c0d84964)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (c0dcf1d4)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (c0e1d9d0)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (c000000000d4ddc4)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (c000000000d7dd1c)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (c000000000ddfaa0)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (c000000000e45a6c)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffe0007bb1b2)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffe0007d93ec)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffe000818ea0)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffe00085cda2)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff81940cb1)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819634f6)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff819aa4c4)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff819f3379)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff818fa7a1)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff8191cfe6)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81963f84)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff819b0139)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff81991e41)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819cdcc6)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81a14d64)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81a5ddf9)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
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
In net/netlink/af_netlink.c (ffffffff819b4931)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_unicast
```
```
In net/ipv4/tcp.c (ffffffff819d7856)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/nexthop.c (ffffffff81a1f774)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_notify
  - net/ipv4/nexthop.c:nexthop_notify
```
```
In net/ipv6/route.c (ffffffff81a6a209)
Location: include/net/sock.h:2276
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:ip6_route_del
```
</details>
</li>
</ul>

## Differences
