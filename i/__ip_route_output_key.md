# Function: <code>__ip_route_output_key</code>

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
In net/ipv4/route.c (ffffffff81756b76)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177c743)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81784000)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff8178e42a)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/af_inet.c (ffffffff81794641)
Location: include/net/route.h:120
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af5d9)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
  - net/ipv4/xfrm4_policy.c:xfrm4_get_saddr
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
In net/ipv4/route.c (ffffffff817c30c1)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea089)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff817f1592)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff817fba1f)
Location: include/net/route.h:120
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/af_inet.c (ffffffff81801feb)
Location: include/net/route.h:120
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c4ea)
Location: include/net/route.h:120
Inline: True
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
In net/ipv4/route.c (ffffffff817f1841)
Location: include/net/route.h:119
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181a806)
Location: include/net/route.h:119
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff8182216e)
Location: include/net/route.h:119
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff8182c95c)
Location: include/net/route.h:119
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
```
In net/ipv4/af_inet.c (ffffffff81832f7a)
Location: include/net/route.h:119
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184ddaa)
Location: include/net/route.h:119
Inline: True
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
In net/ipv4/route.c (ffffffff818130d1)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183afec)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81842de1)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff8184dd74)
Location: include/net/route.h:122
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818542a1)
Location: include/net/route.h:122
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818717fa)
Location: include/net/route.h:122
Inline: True
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
In net/ipv4/route.c (ffffffff81892711)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bac1c)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff818c2744)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff818cd9e2)
Location: include/net/route.h:122
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff818d4121)
Location: include/net/route.h:122
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818f21c0)
Location: include/net/route.h:122
Inline: True
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
In net/ipv4/route.c (ffffffff818e66c5)
Location: include/net/route.h:121
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190f6ac)
Location: include/net/route.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff8191839b)
Location: include/net/route.h:121
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81923d90)
Location: include/net/route.h:121
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8192a688)
Location: include/net/route.h:121
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948b14)
Location: include/net/route.h:121
Inline: True
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
In net/ipv4/route.c (ffffffff81913515)
Location: include/net/route.h:121
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193dad3)
Location: include/net/route.h:121
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81946af1)
Location: include/net/route.h:121
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81952b7a)
Location: include/net/route.h:121
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81959e18)
Location: include/net/route.h:121
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197a7e4)
Location: include/net/route.h:121
Inline: True
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
In net/ipv4/route.c (ffffffff81975b55)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a1ed6)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819ab166)
Location: include/net/route.h:122
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff819b7489)
Location: include/net/route.h:122
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819be79e)
Location: include/net/route.h:122
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819e433c)
Location: include/net/route.h:122
Inline: True
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
In net/ipv4/route.c (ffffffff819ac565)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d8b8c)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819e1e34)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff819ee189)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819f53ce)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a1b34c)
Location: include/net/route.h:123
Inline: True
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
In net/ipv4/route.c (ffffffff81a96a2b)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac55d3)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81acf6a6)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81adbf4d)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81ae3761)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b0c404)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
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
In net/ipv4/route.c (ffffffff81aa0add)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1251)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81adb6ab)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81ae8aaa)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81af02e1)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sk_reselect_saddr
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b1a678)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
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
In net/ipv4/route.c (ffffffff81a8ba0d)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abc242)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81ac671b)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81ad3d5d)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81adb991)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b08308)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
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
In net/ipv4/route.c (ffffffff81b4699d)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b79342)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81b84f2b)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81b92a1d)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81b9abd1)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81bcb218)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
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
In net/ipv4/route.c (ffffffff81cd3a08)
Location: include/net/route.h:137
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0889b)
Location: include/net/route.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81d157d3)
Location: include/net/route.h:137
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81d23fc1)
Location: include/net/route.h:137
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81d2c5f0)
Location: include/net/route.h:137
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81d60be4)
Location: include/net/route.h:137
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
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
In net/ipv4/route.c (ffffffff81e93c28)
Location: include/net/route.h:137
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecedfb)
Location: include/net/route.h:137
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81edb9b1)
Location: include/net/route.h:137
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81eeb651)
Location: include/net/route.h:137
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81ef4f22)
Location: include/net/route.h:137
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f2b585)
Location: include/net/route.h:137
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_lookup
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
In net/ipv4/route.c (ffffffff81ef23d8)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2d182)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81f3aa76)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81f4af84)
Location: include/net/route.h:131
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81f54802)
Location: include/net/route.h:131
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f8af84)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
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
In net/ipv4/route.c (ffffffff81fb6538)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff201b)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff82000b6c)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff8201109c)
Location: include/net/route.h:131
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8201aa5c)
Location: include/net/route.h:131
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff82052664)
Location: include/net/route.h:131
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
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
In net/ipv4/route.c (ffff800010c5c68c)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8d7b4)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffff800010c95ecc)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffff800010ca3ce8)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffff800010cab110)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffff800010cd73dc)
Location: include/net/route.h:123
Inline: True
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
In net/ipv4/route.c (c0d6bd9c)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (c0d9b808)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (c0da4688)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (c0db0980)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (c0db7af4)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (c0de1060)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:__xfrm4_dst_lookup
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
In net/ipv4/route.c (c000000000d5eb18)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9a260)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (c000000000da70c4)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (c000000000db76e0)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (c000000000dc1598)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (c000000000df72fc)
Location: include/net/route.h:123
Inline: True
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
In net/ipv4/route.c (ffffffe0007c55f4)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ed160)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffe0007f4ec4)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffe0007ffb90)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffe000805d1a)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffe000827c92)
Location: include/net/route.h:123
Inline: True
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
In net/ipv4/route.c (ffffffff8194c3d5)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819789fc)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff81981ca4)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff8198df29)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8199516e)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819ba9dc)
Location: include/net/route.h:123
Inline: True
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
In net/ipv4/route.c (ffffffff81905ec5)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819324bc)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff8193b764)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff819479e9)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff8194ec2e)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819777cc)
Location: include/net/route.h:123
Inline: True
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
In net/ipv4/route.c (ffffffff819b6ba5)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e31cc)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819ec474)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff819f87c9)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff819ffa0e)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a2545c)
Location: include/net/route.h:123
Inline: True
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
In net/ipv4/route.c (ffffffff819c0415)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_flow
  - net/ipv4/route.c:ipv4_sk_redirect
  - net/ipv4/route.c:ipv4_redirect
  - net/ipv4/route.c:ipv4_update_pmtu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ed2ec)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
```
In net/ipv4/datagram.c (ffffffff819f6332)
Location: include/net/route.h:123
Inline: True
Inline callers:
  - net/ipv4/datagram.c:__ip4_datagram_connect
```
```
In net/ipv4/icmp.c (ffffffff81a02b37)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/af_inet.c (ffffffff81a09b18)
Location: include/net/route.h:123
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a308d8)
Location: include/net/route.h:123
Inline: True
```
</details>
</li>
</ul>

## Differences
