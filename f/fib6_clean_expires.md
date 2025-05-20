# Function: <code>fib6_clean_expires</code>

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
In net/ipv6/addrconf.c (ffffffff8196d3f9)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81976b97)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff8197b9f4)
Location: include/net/ip6_fib.h:207
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/addrconf.c (ffffffff819a2f51)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff819ac784)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff819b16d4)
Location: include/net/ip6_fib.h:210
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/ipv6/addrconf.c (ffffffff81a0df81)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81a1b05a)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1fc52)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81a3fa40)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81a51cda)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5680a)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81b3473c)
Location: include/net/ip6_fib.h:248
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81b493aa)
Location: include/net/ip6_fib.h:248
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4e30d)
Location: include/net/ip6_fib.h:248
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81b4320c)
Location: include/net/ip6_fib.h:249
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81b57fba)
Location: include/net/ip6_fib.h:249
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5cf9b)
Location: include/net/ip6_fib.h:249
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81b30f2c)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81b45c4c)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4b1b6)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81bf744c)
Location: include/net/ip6_fib.h:252
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81c0cdae)
Location: include/net/ip6_fib.h:252
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81c124f6)
Location: include/net/ip6_fib.h:252
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81d9a2f7)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81da7e25)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81dadbcd)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81f69120)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81f77475)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7d5f9)
Location: include/net/ip6_fib.h:253
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81fc9210)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81fd7415)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdd806)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff82096992)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff820a4d95)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff820ab864)
Location: include/net/ip6_fib.h:250
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffff800010cffc34)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffff800010d15c20)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffff800010d1b36c)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (c0e08170)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (c0e1b954)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (c0e207f8)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (c000000000e29e40)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (c000000000e42f70)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (c000000000e49924)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffe000849120)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffe00085b20c)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffe00085f36e)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff819df0d0)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff819f136a)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff819f5e9a)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff8199be90)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff819ae12a)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff819b2c5a)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81a49b50)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81a5bdea)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6091a)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
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
In net/ipv6/addrconf.c (ffffffff81a55a90)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
```
In net/ipv6/route.c (ffffffff81a6815a)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6cdda)
Location: include/net/ip6_fib.h:215
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
</details>
</li>
</ul>

## Differences
