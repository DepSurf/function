# Function: <code>dst_init_metrics</code>

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
In net/core/dst.c (ffffffff817237c0)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/core/dst.c:dst_init
```
```
In net/ipv4/route.c (ffffffff8175441a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_set_nexthop
```
```
In net/ipv6/route.c (ffffffff817d378a)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_dst_check
```
```
In net/ipv6/ip6_fib.c (ffffffff817db37f)
Location: include/net/dst.h:150
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/core/dst.c (ffffffff8178d220)
Location: include/net/dst.h:147
Inline: True
Inline callers:
  - net/core/dst.c:dst_init
```
```
In net/ipv4/route.c (ffffffff817c05a2)
Location: include/net/dst.h:147
Inline: True
```
```
In net/ipv6/route.c (ffffffff81841c73)
Location: include/net/dst.h:147
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81849393)
Location: include/net/dst.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/core/dst.c (ffffffff817baaf0)
Location: include/net/dst.h:147
Inline: True
Inline callers:
  - net/core/dst.c:dst_init
```
```
In net/ipv4/route.c (ffffffff817ef7b2)
Location: include/net/dst.h:147
Inline: True
```
```
In net/ipv6/route.c (ffffffff81873af3)
Location: include/net/dst.h:147
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_dst_check
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8187b1e4)
Location: include/net/dst.h:147
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/core/dst.c (ffffffff817d9815)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff818107a6)
Location: include/net/dst.h:151
Inline: True
```
```
In net/ipv6/route.c (ffffffff81898793)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_fib.c (ffffffff818a0b4a)
Location: include/net/dst.h:151
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/core/dst.c (ffffffff81853f35)
Location: include/net/dst.h:153
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff8188fc27)
Location: include/net/dst.h:153
Inline: True
```
```
In net/ipv6/route.c (ffffffff81919b33)
Location: include/net/dst.h:153
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8192371f)
Location: include/net/dst.h:153
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
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
In net/core/dst.c (ffffffff8189f6d1)
Location: include/net/dst.h:136
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff818e42c7)
Location: include/net/dst.h:136
Inline: True
```
```
In net/ipv6/route.c (ffffffff81971650)
Location: include/net/dst.h:136
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff818c2091)
Location: include/net/dst.h:136
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff819111db)
Location: include/net/dst.h:136
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a6f70)
Location: include/net/dst.h:136
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff8190e7ef)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff81973851)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a13520)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81940e4f)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff819aa25f)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4a110)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81a10cdf)
Location: include/net/dst.h:124
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/route.c (ffffffff81a937ab)
Location: include/net/dst.h:124
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b40c70)
Location: include/net/dst.h:124
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81a1108f)
Location: include/net/dst.h:124
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/route.c (ffffffff81a9d65b)
Location: include/net/dst.h:124
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b4f720)
Location: include/net/dst.h:124
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff819f7eff)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/route.c (ffffffff81a885eb)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffff81b3d450)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81aa9b3f)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/route.c (ffffffff81b42d4b)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffff81c03d10)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81c21fbf)
Location: include/net/dst.h:126
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/route.c (ffffffff81ccf7aa)
Location: include/net/dst.h:126
Inline: True
```
```
In net/ipv6/route.c (ffffffff81d9dde0)
Location: include/net/dst.h:126
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81dd411f)
Location: include/net/dst.h:126
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/route.c (ffffffff81e8f9ba)
Location: include/net/dst.h:126
Inline: True
```
```
In net/ipv6/route.c (ffffffff81f6cdc0)
Location: include/net/dst.h:126
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81e44eae)
Location: include/net/dst.h:140
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/route.c (ffffffff81eee0ba)
Location: include/net/dst.h:140
Inline: True
```
```
In net/ipv6/route.c (ffffffff81fccf00)
Location: include/net/dst.h:140
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81f03b2e)
Location: include/net/dst.h:140
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
```
In net/ipv4/route.c (ffffffff81fb221a)
Location: include/net/dst.h:140
Inline: True
```
```
In net/ipv6/route.c (ffffffff8209a715)
Location: include/net/dst.h:140
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (0)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv4/route.c (ffff800010c5a498)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffff800010d0d2f4)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (c0cfaffc)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (c0d69a7c)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (c0e13aa0)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (c000000000cc1b64)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv4/route.c (c000000000d5bf88)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (c000000000e38d3c)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffe000766c00)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:dst_init
```
```
In net/ipv4/route.c (ffffffe0007c39da)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffe000854c2e)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff818e0e1f)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff8194a0cf)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffff819e97a0)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff8189ac5f)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff81903bbf)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a6560)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff81931e4f)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff819b489f)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a54220)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
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
In net/core/dst.c (ffffffff8195351f)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
```
In net/ipv4/route.c (ffffffff819bdfdf)
Location: include/net/dst.h:125
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a60210)
Location: include/net/dst.h:125
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_route_net_init
  - net/ipv6/route.c:ip6_rt_copy_init
```
</details>
</li>
</ul>

## Differences
