# Function: <code>fib6_info_nh_dev</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (0)
Location: include/net/ip6_fib.h:416
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/ip6_fib.h:416
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/ip6_fib.h:416
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/ip6_fib.h:416
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
In net/ipv6/anycast.c (0)
Location: include/net/ip6_fib.h:441
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/net/ip6_fib.h:441
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/net/ip6_fib.h:441
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/net/ip6_fib.h:441
Inline: True
```
```
In net/ipv6/fib6_rules.c (0)
Location: include/net/ip6_fib.h:441
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
In net/ipv6/anycast.c (ffffffff81a002ae)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a007a3)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a0977e)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a14324)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81a36e91)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a37373)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a4046e)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a4af14)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81b2c16b)
Location: include/net/nexthop.h:389
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b2c8a0)
Location: include/net/nexthop.h:389
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81b34332)
Location: include/net/nexthop.h:389
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b45480)
Location: include/net/nexthop.h:389
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81b3ab8c)
Location: include/net/nexthop.h:447
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b3b294)
Location: include/net/nexthop.h:447
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81b44b82)
Location: include/net/nexthop.h:447
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b53e23)
Location: include/net/nexthop.h:447
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:__rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81b2886c)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81b29087)
Location: include/net/nexthop.h:523
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81b32852)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81b413f9)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81bee840)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81bf01d7)
Location: include/net/nexthop.h:523
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81bf8ba0)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81c090e4)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81d86dc3)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81d8887a)
Location: include/net/nexthop.h:523
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81d920d0)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81da3b8f)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81f54983)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81f5665a)
Location: include/net/nexthop.h:523
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81f607e0)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81f72fcf)
Location: include/net/nexthop.h:523
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81fb4393)
Location: include/net/nexthop.h:500
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81fb6050)
Location: include/net/nexthop.h:500
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81fc0610)
Location: include/net/nexthop.h:500
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff81fd30c5)
Location: include/net/nexthop.h:500
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff82081c43)
Location: include/net/nexthop.h:500
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff82083719)
Location: include/net/nexthop.h:500
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8208dac0)
Location: include/net/nexthop.h:500
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_fill_ifacaddr
```
```
In net/ipv6/route.c (ffffffff820a09d5)
Location: include/net/nexthop.h:500
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffff800010cf7c14)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffff800010cf9f08)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffff800010d016e8)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffff800010d0df24)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (c0dfe16c)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (c0dfe854)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c0e09224)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (c0e1481c)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (c000000000e1e618)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (c000000000e1ed90)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (c000000000e2b6fc)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (c000000000e39ee0)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffe0008433e6)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffe00084b456)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffe000855b3a)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff819d6521)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff819d6a03)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff819dfafe)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff819ea5a4)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff819932e1)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff819937c3)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff8199c8be)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff819a7364)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81a40fa1)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a41483)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a4a57e)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a55024)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
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
In net/ipv6/anycast.c (ffffffff81a4cbac)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_chk_acast_addr
```
```
In net/ipv6/ip6_output.c (ffffffff81a4d08c)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_dst_lookup_tail
```
```
In net/ipv6/addrconf.c (ffffffff81a564be)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:in6_dump_addrs
```
```
In net/ipv6/route.c (ffffffff81a61014)
Location: include/net/nexthop.h:279
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_purge_dflt_routers
```
</details>
</li>
</ul>

## Differences
