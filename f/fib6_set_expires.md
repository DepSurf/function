# Function: <code>fib6_set_expires</code>

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
In net/ipv6/addrconf.c (ffffffff8196d436)
Location: include/net/ip6_fib.h:213
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81976f43)
Location: include/net/ip6_fib.h:213
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff8197bf83)
Location: include/net/ip6_fib.h:213
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff81982165)
Location: include/net/ip6_fib.h:213
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff819a2f8e)
Location: include/net/ip6_fib.h:216
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff819acb2d)
Location: include/net/ip6_fib.h:216
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1c63)
Location: include/net/ip6_fib.h:216
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
```
```
In net/ipv6/ndisc.c (ffffffff819b8863)
Location: include/net/ip6_fib.h:216
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81a0df4d)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a1b2fa)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1fc91)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a272c4)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81a3fa16)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a51f7a)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81a568f7)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a5dd68)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81b34702)
Location: include/net/ip6_fib.h:254
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b496a1)
Location: include/net/ip6_fib.h:254
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4e5ea)
Location: include/net/ip6_fib.h:254
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81b55791)
Location: include/net/ip6_fib.h:254
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81b431d2)
Location: include/net/ip6_fib.h:255
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b582b1)
Location: include/net/ip6_fib.h:255
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5d255)
Location: include/net/ip6_fib.h:255
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81b63df1)
Location: include/net/ip6_fib.h:255
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81b30ef2)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b45f37)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4b490)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81b51aa2)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81bf7412)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81c0d0c3)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81c127d0)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81c18f62)
Location: include/net/ip6_fib.h:258
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81d9a14f)
Location: include/net/ip6_fib.h:259
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81da8107)
Location: include/net/ip6_fib.h:259
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81dadcaa)
Location: include/net/ip6_fib.h:259
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81db51bf)
Location: include/net/ip6_fib.h:259
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81f68f3b)
Location: include/net/ip6_fib.h:259
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81f7777b)
Location: include/net/ip6_fib.h:259
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7d73c)
Location: include/net/ip6_fib.h:259
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81f84dbf)
Location: include/net/ip6_fib.h:259
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81fc9030)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81fd7782)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdd949)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81fe512c)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff820968ba)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff820a5102)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff820aba66)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff820b3013)
Location: include/net/ip6_fib.h:256
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffff800010cffbfc)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffff800010d15ee4)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffff800010d1b3a0)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffff800010d22ddc)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (c0e08180)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (c0e1bc80)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (c0e2080c)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (c0e27314)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (c000000000e29d58)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (c000000000e4332c)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (c000000000e49994)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (c000000000e5224c)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffe0008490ae)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffe00085b450)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffe00085f502)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffe000864212)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff819df0a6)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff819f160a)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff819f5f87)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff819fd3f8)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff8199be66)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff819ae3ca)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff819b2d47)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff819ba1b8)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81a49b26)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a5c08a)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81a60a07)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a67e78)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/ipv6/addrconf.c (ffffffff81a55a66)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:cleanup_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a683fa)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6cec7)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
```
In net/ipv6/ndisc.c (ffffffff81a74467)
Location: include/net/ip6_fib.h:221
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
</ul>

## Differences
