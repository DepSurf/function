# Function: <code>dst_metrics_ptr</code>

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
In net/ipv4/route.c (0)
Location: include/net/dst.h:169
Inline: True
```
```
In net/ipv6/route.c (ffffffff817d4cb8)
Location: include/net/dst.h:169
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_dst_check
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
In net/ipv4/route.c (ffffffff817bfdf0)
Location: include/net/dst.h:166
Inline: True
```
```
In net/ipv6/route.c (ffffffff818412ba)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv4/route.c (ffffffff817f2f12)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv6/route.c (ffffffff81872fba)
Location: include/net/dst.h:166
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:170
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898d39)
Location: include/net/dst.h:170
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:172
Inline: True
```
```
In net/ipv6/route.c (ffffffff8191a039)
Location: include/net/dst.h:172
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:155
Inline: True
```
```
In net/ipv6/route.c (ffffffff81972112)
Location: include/net/dst.h:155
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:155
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a786a)
Location: include/net/dst.h:155
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a13ec2)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4aab2)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (ffffffff81a91323)
Location: include/net/dst.h:143
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv6/route.c (ffffffff81b45010)
Location: include/net/dst.h:143
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (ffffffff81a9b19c)
Location: include/net/dst.h:143
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv6/route.c (ffffffff81b53990)
Location: include/net/dst.h:143
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (ffffffff81a865bc)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv6/route.c (ffffffff81b40f52)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (ffffffff81b40cfc)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv6/route.c (ffffffff81c08c22)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (ffffffff81ccd7dd)
Location: include/net/dst.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv6/route.c (ffffffff81da374b)
Location: include/net/dst.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (ffffffff81e8d91e)
Location: include/net/dst.h:145
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv6/route.c (ffffffff81f72b8b)
Location: include/net/dst.h:145
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (ffffffff81eec04d)
Location: include/net/dst.h:159
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv6/route.c (ffffffff81fd2c7e)
Location: include/net/dst.h:159
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (ffffffff81fb009d)
Location: include/net/dst.h:159
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_fill_info
```
```
In net/ipv6/route.c (ffffffff820a058e)
Location: include/net/dst.h:159
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0db70)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (c0e1441c)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (c000000000e39994)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (ffffffe0008557fe)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ea142)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a6f02)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54bc2)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
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
In net/ipv4/route.c (0)
Location: include/net/dst.h:144
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60bb2)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_fill_node
```
</details>
</li>
</ul>

## Differences
