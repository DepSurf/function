# Function: <code>__neigh_lookup</code>

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
In net/core/neighbour.c (ffffffff81729333)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff8178cc4e)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff817d796b)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff817df77c)
Location: include/net/neighbour.h:472
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
In net/core/neighbour.c (ffffffff81792e03)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff817fa396)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff818461ca)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff8184edf2)
Location: include/net/neighbour.h:472
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
In net/core/neighbour.c (ffffffff817c06d3)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff8182b266)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81877f2a)
Location: include/net/neighbour.h:472
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81880d42)
Location: include/net/neighbour.h:472
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
In net/core/neighbour.c (ffffffff817ded93)
Location: include/net/neighbour.h:485
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff8184c3b9)
Location: include/net/neighbour.h:485
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8189d0e4)
Location: include/net/neighbour.h:485
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff818a6d82)
Location: include/net/neighbour.h:485
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
In net/core/neighbour.c (ffffffff81859633)
Location: include/net/neighbour.h:486
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff818cc069)
Location: include/net/neighbour.h:486
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8191ca87)
Location: include/net/neighbour.h:486
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff819297de)
Location: include/net/neighbour.h:486
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
In net/core/neighbour.c (ffffffff818a4ba3)
Location: include/net/neighbour.h:487
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81922443)
Location: include/net/neighbour.h:487
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819750f9)
Location: include/net/neighbour.h:487
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81981ef0)
Location: include/net/neighbour.h:487
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
In net/core/neighbour.c (ffffffff818c82c3)
Location: include/net/neighbour.h:512
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff8195127e)
Location: include/net/neighbour.h:512
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819aadb0)
Location: include/net/neighbour.h:512
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff819b859a)
Location: include/net/neighbour.h:512
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81914da3)
Location: include/net/neighbour.h:515
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff819b5b2c)
Location: include/net/neighbour.h:515
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a18024)
Location: include/net/neighbour.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81a27013)
Location: include/net/neighbour.h:515
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81947413)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff819ec84c)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a4ec84)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81a5da50)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81a17563)
Location: include/net/neighbour.h:513
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81ada84d)
Location: include/net/neighbour.h:513
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b46586)
Location: include/net/neighbour.h:513
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b551ec)
Location: include/net/neighbour.h:513
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81a17833)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81ae72ed)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b550c6)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b6380c)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff819fe743)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81ad25ad)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81b42b41)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81b51baa)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81ab08a3)
Location: include/net/neighbour.h:520
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81b911fd)
Location: include/net/neighbour.h:520
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81c0829e)
Location: include/net/neighbour.h:520
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81c19320)
Location: include/net/neighbour.h:520
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81c2993e)
Location: include/net/neighbour.h:553
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81d22598)
Location: include/net/neighbour.h:553
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81da3069)
Location: include/net/neighbour.h:553
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81db558a)
Location: include/net/neighbour.h:553
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81ddc66e)
Location: include/net/neighbour.h:550
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81ee9a28)
Location: include/net/neighbour.h:550
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81f72479)
Location: include/net/neighbour.h:550
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81f8518a)
Location: include/net/neighbour.h:550
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81e4d3ce)
Location: include/net/neighbour.h:548
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81f4935b)
Location: include/net/neighbour.h:548
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81fd2569)
Location: include/net/neighbour.h:548
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81fe5348)
Location: include/net/neighbour.h:548
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81f0c12e)
Location: include/net/neighbour.h:546
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff8200f4da)
Location: include/net/neighbour.h:546
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff8209faf9)
Location: include/net/neighbour.h:546
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff820b3216)
Location: include/net/neighbour.h:546
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffff800010be8808)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffff800010ca2390)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffff800010d12998)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffff800010d22898)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (c0d019e0)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (c0daf1f4)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (c0e18804)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (c0e27c44)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_rcv
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (c000000000ccadcc)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (c000000000db5988)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (c000000000e3f084)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (c000000000e524f4)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffe00076ccac)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffe0007fe47a)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffe000858e3c)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffe0008643ce)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff818e73e3)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff8198c6b7)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819ee314)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff819fd0e0)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff818a1223)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81946177)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff819ab0d4)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff819b9ea0)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81938413)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff819f6e8c)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a58d94)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81a67b60)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
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
In net/core/neighbour.c (ffffffff81959c23)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_event_ns
```
```
In net/ipv4/arp.c (ffffffff81a010ac)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv6/route.c (ffffffff81a64f74)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_do_redirect
```
```
In net/ipv6/ndisc.c (ffffffff81a7414f)
Location: include/net/neighbour.h:514
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
```
</details>
</li>
</ul>

## Differences
