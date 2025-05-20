# Function: <code>rt6_set_expires</code>

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
In net/ipv6/addrconf.c (ffffffff817c9cf1)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff817d63d4)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff817dba3e)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff817df50c)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff8183e631)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81844984)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff818499e1)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff8184eb78)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81870241)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81876700)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff8187b86e)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff81880ac8)
Location: include/net/ip6_fib.h:149
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81895031)
Location: include/net/ip6_fib.h:152
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff8189be27)
Location: include/net/ip6_fib.h:152
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff818a1266)
Location: include/net/ip6_fib.h:152
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff818a73f4)
Location: include/net/ip6_fib.h:152
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff819164f6)
Location: include/net/ip6_fib.h:196
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff8191eada)
Location: include/net/ip6_fib.h:196
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81923b92)
Location: include/net/ip6_fib.h:196
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff81929e56)
Location: include/net/ip6_fib.h:196
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
