# Function: <code>rtnh_next</code>

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
In net/ipv4/fib_semantics.c (ffffffff8179c6f7)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff817d428a)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/ipv4/fib_semantics.c (ffffffff8180a44a)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff818179c2)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff818419ea)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff817d96e2)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b55a)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff8184922f)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8187386a)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff817f8b30)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185ce4e)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff8186c7fb)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8189ae91)
Location: include/net/nexthop.h:14
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81876410)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff818dce6e)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff818ed0e1)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8191be81)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff818c7b56)
Location: include/net/nexthop.h:15
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819339f5)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff8194308c)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81974747)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff818f0cb6)
Location: include/net/nexthop.h:15
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81962ee8)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff8197321e)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff819aa017)
Location: include/net/nexthop.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff819423ca)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8e6c)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff819dcd1b)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81a1895f)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff819772fa)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffa2c)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81a13d84)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81a4f5bf)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81a4c0ea)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeefb9)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81b00ae0)
Location: include/net/rtnh.h:15
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b46cff)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81a51d1a)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbf35)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81b0ebc0)
Location: include/net/rtnh.h:15
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b558ff)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81a3761a)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae770f)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81afc8b0)
Location: include/net/rtnh.h:15
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4350f)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81aed30a)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba7581)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81bbdfdf)
Location: include/net/rtnh.h:15
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c0a082)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81c6ff87)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3a441)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81d52aab)
Location: include/net/rtnh.h:15
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da45c7)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81e27ed7)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02da1)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81f1cdde)
Location: include/net/rtnh.h:15
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f73a37)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81e9d4e7)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f622c5)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81f7c8ae)
Location: include/net/rtnh.h:15
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd3b17)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff81f5fc69)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff82028895)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff82042fa5)
Location: include/net/rtnh.h:15
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a1428)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffff800010c1dc78)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb8010)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffff800010cce3b4)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffff800010d10e10)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (c0d358f4)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (c0dc33f0)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (c0dd9484)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (c0e19094)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (c000000000d0f200)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (c000000000dd0874)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (c000000000deb004)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (c000000000e3fc3c)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffe0007977fc)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080f038)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffe0008206d8)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffe00085838e)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff8191716a)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f7cc)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff819b350b)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff819eec4f)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff818d0f1a)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8195928c)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff8196fb3b)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff819aba0f)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff819682fa)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a06c)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81a1ddab)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81a596cf)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
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
In net/core/lwtunnel.c (ffffffff8198a5ba)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a1484c)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81a29074)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81a6590f)
Location: include/net/rtnh.h:15
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
```
</details>
</li>
</ul>

## Differences
