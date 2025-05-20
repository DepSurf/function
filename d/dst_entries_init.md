# Function: <code>dst_entries_init</code>

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
In net/ipv4/route.c (ffffffff81fbc8a7)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff817af47b)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff817d44d4)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fc0db)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff81fea712)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8181c37b)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff81febed8)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b9db)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff82028fc5)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8184dc3b)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8202a7db)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e83b)
Location: include/net/dst_ops.h:64
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8210c530)
Location: include/net/dst_ops.h:59
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8187168b)
Location: include/net/dst_ops.h:59
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8210df3e)
Location: include/net/dst_ops.h:59
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4c5b)
Location: include/net/dst_ops.h:59
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8271689c)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff818f204b)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff827182f3)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81947cdb)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff82740bfc)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81948933)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff82742a1d)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a0e93)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff828fae2d)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197a603)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff828fcd10)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7ac3)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8291782f)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819e4103)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8291984e)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46ad3)
Location: include/net/dst_ops.h:60
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8292169e)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a1b103)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff829236bd)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d683)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff82d2dc81)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b0c0c3)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff82d2fa06)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b77f73)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8301c7d7)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b1a443)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8301e5f5)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b86eb3)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff83227913)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b080e3)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff832296e8)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b75b83)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff83311cd4)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81bcafe3)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff83313cf7)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c405f3)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff834cbbac)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81d60983)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff834ce092)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddec53)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff83f0e238)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f2b403)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff83f111cb)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb1013)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff83734848)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f8b163)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8373781b)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820116c3)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff83968dfd)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8205284a)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8396becb)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e065a)
Location: include/net/dst_ops.h:63
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffff8000114b2148)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffff800010cd7260)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffff8000114b4540)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48828)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
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
In net/ipv4/route.c (c15b7400)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (c0de0e14)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (c15b9880)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (c0e49d38)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
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
In net/ipv4/route.c (c0000000013c2fe0)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (c000000000df6fe0)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (c0000000013c6018)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7da30)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffe000040e00)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffe000827a52)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffe000043328)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881e76)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff829063a2)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819ba793)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff829083c1)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1cd13)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff828fe6f0)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81977583)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8290070f)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9ad3)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff8291bc85)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a25213)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8291dcbb)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87793)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
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
In net/ipv4/route.c (ffffffff82922700)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:ip_rt_init
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a30683)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
```
```
In net/ipv6/route.c (ffffffff8292471f)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_net_init
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a94363)
Location: include/net/dst_ops.h:61
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
</details>
</li>
</ul>

## Differences
