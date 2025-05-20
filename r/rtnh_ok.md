# Function: <code>rtnh_ok</code>

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
In net/ipv4/fib_semantics.c (ffffffff8179c655)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff817d41ef)
Location: include/net/nexthop.h:7
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
In net/ipv4/fib_semantics.c (ffffffff8180a435)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff81817940)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8184194f)
Location: include/net/nexthop.h:7
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
In net/core/lwtunnel.c (ffffffff817d9675)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183b545)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff818491ad)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff818737cf)
Location: include/net/nexthop.h:7
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
In net/core/lwtunnel.c (ffffffff817f8b05)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185ce1f)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff8186c7b4)
Location: include/net/nexthop.h:7
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8189ae46)
Location: include/net/nexthop.h:7
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
In net/core/lwtunnel.c (ffffffff818763e5)
Location: include/net/nexthop.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff818dce3f)
Location: include/net/nexthop.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff818ed09a)
Location: include/net/nexthop.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff8191be36)
Location: include/net/nexthop.h:8
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
In net/core/lwtunnel.c (ffffffff818c7b25)
Location: include/net/nexthop.h:8
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff819339db)
Location: include/net/nexthop.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff8194305f)
Location: include/net/nexthop.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff819746af)
Location: include/net/nexthop.h:8
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
In net/core/lwtunnel.c (ffffffff818f0c85)
Location: include/net/nexthop.h:8
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81962ece)
Location: include/net/nexthop.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (ffffffff819731f5)
Location: include/net/nexthop.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff819a9f7f)
Location: include/net/nexthop.h:8
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
In net/core/lwtunnel.c (ffffffff81942395)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c8e47)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff819dccf5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81a188cf)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff819772c5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff819ffa07)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81a13d5e)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81a4f52f)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81a4c0b5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeef91)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81b00ab8)
Location: include/net/rtnh.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b46c6f)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81a51ce5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afbf0d)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81b0eb98)
Location: include/net/rtnh.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b5586f)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81a375e5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae76ee)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81afc888)
Location: include/net/rtnh.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4347f)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81aed2d5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba751d)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81bbdf7c)
Location: include/net/rtnh.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c09fa7)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81c6ff45)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39ee1)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81d52a51)
Location: include/net/rtnh.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81da44ba)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81e27e95)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f02841)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81f1cd8c)
Location: include/net/rtnh.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f7392a)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81e9d4a5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f6229d)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81f7c848)
Location: include/net/rtnh.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fd3a0a)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81f5fc25)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8202886d)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff82042f3f)
Location: include/net/rtnh.h:8
Inline: True
```
```
In net/ipv6/route.c (ffffffff820a131a)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffff800010c1dc3c)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7fe0)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffff800010cce37c)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffff800010d10d6c)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (c0d358c4)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (c0dc33ac)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/ipmr.c (c0dd944c)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (c0e18ff4)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (c000000000d0f1a0)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (c000000000dd083c)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (c000000000deafcc)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (c000000000e3fbb0)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffe0007977ce)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080f026)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffe0008205aa)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffe00085831a)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff81917135)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f7a7)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff819b34e5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff819eebbf)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff818d0ee5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81959267)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff8196fb15)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff819ab97f)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff819682c5)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0a047)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81a1dd85)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81a5963f)
Location: include/net/rtnh.h:8
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
In net/core/lwtunnel.c (ffffffff8198a585)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a14827)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv4/ipmr.c (ffffffff81a2904e)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
```
In net/ipv6/route.c (ffffffff81a6587f)
Location: include/net/rtnh.h:8
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
```
</details>
</li>
</ul>

## Differences
