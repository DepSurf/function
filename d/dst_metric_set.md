# Function: <code>dst_metric_set</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b29d4)
Location: include/net/dst.h:202
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
```
In net/ipv6/route.c (ffffffff817d4a5f)
Location: include/net/dst.h:202
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
```
```
In net/ipv6/ndisc.c (ffffffff817df56c)
Location: include/net/dst.h:202
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/xfrm/xfrm_policy.c (ffffffff8181fe20)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff8184295f)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
```
```
In net/ipv6/ndisc.c (ffffffff8184f086)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/xfrm/xfrm_policy.c (ffffffff81851680)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff818746d6)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
```
```
In net/ipv6/ndisc.c (ffffffff81880fdc)
Location: include/net/dst.h:199
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/xfrm/xfrm_policy.c (ffffffff8187391c)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff81898a5a)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
```
```
In net/ipv6/ndisc.c (ffffffff818a701b)
Location: include/net/dst.h:203
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/xfrm/xfrm_policy.c (ffffffff818f4284)
Location: include/net/dst.h:205
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff8191a58a)
Location: include/net/dst.h:205
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
```
```
In net/ipv6/ndisc.c (ffffffff81929a7a)
Location: include/net/dst.h:205
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
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
In net/xfrm/xfrm_policy.c (ffffffff8194ad46)
Location: include/net/dst.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff81972b9d)
Location: include/net/dst.h:188
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff8197ed58)
Location: include/net/dst.h:188
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819a853d)
Location: include/net/dst.h:188
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff819e7c8a)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a1492d)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81a1ec88)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a4b51d)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81b0f331)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/ipv6/route.c (ffffffff81b48c33)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81b1d621)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/ipv6/route.c (ffffffff81b57848)
Location: include/net/dst.h:176
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81b0c01c)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/ipv6/route.c (ffffffff81b45424)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81bceffb)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/ipv6/route.c (ffffffff81c0c564)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81d64fdf)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
```
```
In net/ipv6/route.c (ffffffff81da746c)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81f2fe7f)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81f76a9c)
Location: include/net/dst.h:178
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81f9090f)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81fd6acf)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff8205e672)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff820a4449)
Location: include/net/dst.h:192
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffff800010cdb098)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffff800010d11a84)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (c0de4ee0)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (c0e14eb8)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (c000000000e00080)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (c000000000e3b5b8)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffe00082ca2a)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffe00085644c)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff819be318)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819eabad)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/ipv4/ip_tunnel.c (ffffffff81966c98)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197b108)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819a796d)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81a28d98)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a5562d)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
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
In net/xfrm/xfrm_policy.c (ffffffff81a343a0)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a6162d)
Location: include/net/dst.h:177
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
```
</details>
</li>
</ul>

## Differences
