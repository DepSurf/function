# Function: <code>rtnh_attrs</code>

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
In net/ipv4/fib_semantics.c (ffffffff8179c69d)
Location: include/net/nexthop.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_create_info
```
```
In net/ipv6/route.c (ffffffff817d6783)
Location: include/net/nexthop.h:23
Inline: True
Inline callers:
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
In net/ipv4/fib_semantics.c (ffffffff8180a9b1)
Location: include/net/nexthop.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv6/route.c (ffffffff818419ae)
Location: include/net/nexthop.h:23
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
In net/core/lwtunnel.c (ffffffff817d96a9)
Location: include/net/nexthop.h:23
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8183babf)
Location: include/net/nexthop.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv6/route.c (ffffffff8187382e)
Location: include/net/nexthop.h:23
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
In net/core/lwtunnel.c (ffffffff817f8b5e)
Location: include/net/nexthop.h:23
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8185d480)
Location: include/net/nexthop.h:23
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv6/route.c (ffffffff8189aee3)
Location: include/net/nexthop.h:23
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
In net/core/lwtunnel.c (ffffffff8187643e)
Location: include/net/nexthop.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff818dd4b9)
Location: include/net/nexthop.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv6/route.c (ffffffff8191bed3)
Location: include/net/nexthop.h:24
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
In net/core/lwtunnel.c (ffffffff818c7b81)
Location: include/net/nexthop.h:24
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff8193453f)
Location: include/net/nexthop.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv6/route.c (ffffffff81974793)
Location: include/net/nexthop.h:24
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
In net/core/lwtunnel.c (ffffffff818f0ce1)
Location: include/net/nexthop.h:24
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffff81963e05)
Location: include/net/nexthop.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv6/route.c (ffffffff819aa063)
Location: include/net/nexthop.h:24
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
In net/core/lwtunnel.c (ffffffff819423e1)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff819c89b4)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81a18980)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81977311)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff819ff57b)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81a4f5e0)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81a4c101)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81aeeae4)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81b46d20)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81a51d31)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81afba44)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81b55920)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81a37631)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae71a6)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81b43530)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81aed321)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba6edd)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81c0a01c)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81c6ffa8)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81d39841)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81da4536)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81e27ef8)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f0213c)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81f739a6)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81e9d508)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81f61b9c)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81fd3a86)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81f5fc8c)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8202816c)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff820a1396)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffff800010c1dc94)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffff800010cb7a78)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffff800010d10e2c)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (c0d35914)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (c0dc3a64)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv6/route.c (c0e190a0)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (c000000000d0f240)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (c000000000dd01a0)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (c000000000e3fcd0)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffe00079780e)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffe00080ec20)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffe0008583bc)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81917181)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff8199f31b)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff819eec70)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff818d0f31)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81958ddb)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff819aba30)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff81968311)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a09bbb)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81a596f0)
Location: include/net/rtnh.h:24
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
In net/core/lwtunnel.c (ffffffff8198a5d1)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
```
```
In net/ipv4/fib_semantics.c (ffffffff81a1436b)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/ipv6/route.c (ffffffff81a65930)
Location: include/net/rtnh.h:24
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
```
</details>
</li>
</ul>

## Differences
