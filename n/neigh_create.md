# Function: <code>neigh_create</code>

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
In net/core/neighbour.c (ffffffff8172936c)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
  - net/core/neighbour.c:neigh_add
```
```
In net/ipv4/route.c (ffffffff81754357)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/arp.c (ffffffff8178c97c)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff817d54ab)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_neigh_lookup
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff817df7bb)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_rcv
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
In net/core/neighbour.c (ffffffff81793169)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff817c0423)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/arp.c (ffffffff817f9f77)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81846306)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff8184ee31)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff817c0a39)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff817f0316)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/arp.c (ffffffff8182ae47)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81878066)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81880d81)
Location: include/net/neighbour.h:309
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff817df0de)
Location: include/net/neighbour.h:310
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81810323)
Location: include/net/neighbour.h:310
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/arp.c (ffffffff8184c11a)
Location: include/net/neighbour.h:310
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8189d236)
Location: include/net/neighbour.h:310
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff818a6dab)
Location: include/net/neighbour.h:310
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81859984)
Location: include/net/neighbour.h:311
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff8188fa5a)
Location: include/net/neighbour.h:311
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/arp.c (ffffffff818cbdc0)
Location: include/net/neighbour.h:311
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8191cbdb)
Location: include/net/neighbour.h:311
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81929807)
Location: include/net/neighbour.h:311
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff818a4f4c)
Location: include/net/neighbour.h:312
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff818e3842)
Location: include/net/neighbour.h:312
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/arp.c (ffffffff8192221f)
Location: include/net/neighbour.h:312
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81975121)
Location: include/net/neighbour.h:312
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81981f0b)
Location: include/net/neighbour.h:312
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff818c82d9)
Location: include/net/neighbour.h:318
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff819106ec)
Location: include/net/neighbour.h:318
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:ipv4_neigh_lookup
```
```
In net/ipv4/arp.c (ffffffff8195104f)
Location: include/net/neighbour.h:318
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819aadd8)
Location: include/net/neighbour.h:318
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b85b5)
Location: include/net/neighbour.h:318
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81914db9)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81973109)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff819b5924)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a18046)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a2702e)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81947429)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff819a9a7f)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff819ec644)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a4eca6)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a5da6b)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81a17579)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81a92ed6)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81ada5bc)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b46795)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b55203)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81a17849)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81a9cd7c)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81ae705c)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b552da)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b63823)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff819fe759)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81a87efd)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81ad231c)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b42d4d)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81b51bc1)
Location: include/net/neighbour.h:320
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81ab08b9)
Location: include/net/neighbour.h:321
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81b4246d)
Location: include/net/neighbour.h:321
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81b90f6c)
Location: include/net/neighbour.h:321
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81c084a7)
Location: include/net/neighbour.h:321
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81c1933b)
Location: include/net/neighbour.h:321
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81c2995a)
Location: include/net/neighbour.h:346
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81ccee83)
Location: include/net/neighbour.h:346
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81d222cb)
Location: include/net/neighbour.h:346
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81da3291)
Location: include/net/neighbour.h:346
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81db55b8)
Location: include/net/neighbour.h:346
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81ddc68a)
Location: include/net/neighbour.h:343
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81e8f0ee)
Location: include/net/neighbour.h:343
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81ee974b)
Location: include/net/neighbour.h:343
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81f726a1)
Location: include/net/neighbour.h:343
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81f851b8)
Location: include/net/neighbour.h:343
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81e4d3ea)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81eed704)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81f4907b)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81fd2794)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81fe5376)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81f0c14a)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff81fb1778)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff8200f20b)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8209fd24)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff820b323c)
Location: include/net/neighbour.h:341
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffff800010be8818)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffff800010c59648)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffff800010ca21a4)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffff800010d129bc)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffff800010d228b8)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (c0d019f0)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (c0d691ec)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (c0daef20)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (c0e18824)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c0e27c60)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (c000000000ccae28)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (c000000000d5b52c)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (c000000000db5610)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (c000000000e3f380)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (c000000000e52a30)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffe00076ccfe)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffe0007c32f4)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffe0007fe110)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffe000858fd4)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffe000864756)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff818e73f9)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff819498ef)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff8198c474)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819ee336)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819fd0fb)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff818a1239)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff819033df)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81945f34)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819ab0f6)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff819b9ebb)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81938429)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff819b40bf)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff819f6c84)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a58db6)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a67b7b)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81959c39)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/route.c (ffffffff819bd7af)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/arp.c (ffffffff81a00ea4)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a64f96)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_neigh_lookup
```
```
In net/ipv6/ndisc.c (ffffffff81a7416a)
Location: include/net/neighbour.h:319
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
</details>
</li>
</ul>

## Differences
