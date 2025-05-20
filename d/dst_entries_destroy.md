# Function: <code>dst_entries_destroy</code>

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
In net/ipv4/xfrm4_policy.c (ffffffff817af345)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff817d44b1)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_cleanup
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fbd15)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff8181c245)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff818473a8)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b5e5)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff8184db05)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff818791e8)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e445)
Location: include/net/dst_ops.h:69
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81871565)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8189eb88)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4975)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff818f1f55)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81921138)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81947c15)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff819487c5)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff819794e8)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a0d25)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff8197a495)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff819af0c8)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7945)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff819e3fa5)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81a1d238)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46975)
Location: include/net/dst_ops.h:65
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81a1afa5)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81a53f08)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d525)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81b0c025)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81b4b5a4)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b77ef5)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81b1a3a5)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81b5a234)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b86e35)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81b08045)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81b48414)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75b05)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81bcaf45)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81c0f6e4)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40575)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81d608d5)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81daa874)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddebd5)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81f2b0c5)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81f7a084)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb0dc5)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81f8ad95)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81fda294)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011475)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff820524a5)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff820a7ce4)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0405)
Location: include/net/dst_ops.h:68
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffff800010cd70e0)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffff800010d18008)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d486d0)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (c0de0cf4)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (c0e1dbec)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (c0e49c10)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (c000000000df6d90)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (c000000000e45cf4)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7d7e0)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffe0008278ec)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffe00085cf82)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881d2a)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff819ba635)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff819f3598)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1cbb5)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81977425)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff819b0358)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9975)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81a250b5)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81a5e018)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87635)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
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
In net/ipv4/xfrm4_policy.c (ffffffff81a30525)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81a6a428)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_exit
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a94205)
Location: include/net/dst_ops.h:66
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
</details>
</li>
</ul>

## Differences
