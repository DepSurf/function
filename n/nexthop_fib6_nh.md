# Function: <code>nexthop_fib6_nh</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81a002ba)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a007af)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a0978a)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a14335)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1daa0)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffff81a36e9d)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a3737f)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a4047a)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a4af25)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a546d0)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffff81b2c113)
Location: include/net/nexthop.h:369
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c8ac)
Location: include/net/nexthop.h:369
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81b34342)
Location: include/net/nexthop.h:369
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b4548d)
Location: include/net/nexthop.h:369
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4bab1)
Location: include/net/nexthop.h:369
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffff81b3ab38)
Location: include/net/nexthop.h:404
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b2a0)
Location: include/net/nexthop.h:404
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81b44b92)
Location: include/net/nexthop.h:404
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b53e30)
Location: include/net/nexthop.h:404
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
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
In net/ipv6/anycast.c (ffffffff81b28818)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b29093)
Location: include/net/nexthop.h:480
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b32862)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b41406)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
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
In net/ipv6/anycast.c (ffffffff81bee7d5)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81bf01e7)
Location: include/net/nexthop.h:480
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bf8bb0)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81c090f1)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
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
In net/ipv6/anycast.c (ffffffff81d86d53)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81d8888a)
Location: include/net/nexthop.h:480
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d920e0)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81da3b9f)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
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
In net/ipv6/anycast.c (ffffffff81f54913)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81f5666a)
Location: include/net/nexthop.h:480
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f607f0)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81f72fdf)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
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
In net/ipv6/anycast.c (ffffffff81fb4323)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6060)
Location: include/net/nexthop.h:480
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fc0620)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81fd30d5)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81fda9a2)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffff82081bd3)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff82083729)
Location: include/net/nexthop.h:480
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208dad0)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff820a09e5)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:rt6_device_match
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff820a83f2)
Location: include/net/nexthop.h:480
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffff800010cf7c1c)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffff800010cf9f10)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffff800010d016f0)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffff800010d0df2c)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffff800010d1896c)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (c0dfe17c)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (c0dfe864)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c0e09234)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (c0e1482c)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (c0e1eb34)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (c000000000e1e624)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (c000000000e1ed9c)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c000000000e2b708)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (c000000000e39eec)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (c000000000e46a64)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffe000842e7a)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffe0008433ea)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffe00084b45a)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffe000855b40)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffe00085d94c)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffff819d652d)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff819d6a0f)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff819dfb0a)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff819ea5b5)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff819f3d60)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffff819932ed)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff819937cf)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff8199c8ca)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff819a7375)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0b20)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffff81a40fad)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a4148f)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a4a58a)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a55035)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5e7e0)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
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
In net/ipv6/anycast.c (ffffffff81a4cbb8)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d09c)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a564ca)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a61025)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:ip6_pol_route_lookup
  - net/ipv6/route.c:__find_rr_leaf
  - net/ipv6/route.c:fib6_select_path
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6ac60)
Location: include/net/nexthop.h:262
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:ipv6_route_seq_show
```
</details>
</li>
</ul>

## Differences
