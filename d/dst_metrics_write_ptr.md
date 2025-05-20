# Function: <code>dst_metrics_write_ptr</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b25fd)
Location: include/net/dst.h:136
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
```
```
In net/ipv6/route.c (ffffffff817d4a5f)
Location: include/net/dst.h:136
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:icmp6_dst_alloc
```
```
In net/ipv6/ip6_fib.c (ffffffff817d9da5)
Location: include/net/dst.h:136
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff817df56c)
Location: include/net/dst.h:136
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
In net/xfrm/xfrm_policy.c (ffffffff8181fe51)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff8184295f)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81847f05)
Location: include/net/dst.h:133
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8184f086)
Location: include/net/dst.h:133
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
In net/xfrm/xfrm_policy.c (ffffffff818516b1)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff818746d6)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81879d45)
Location: include/net/dst.h:133
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff81880fdc)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 *dst_metrics_write_ptr(struct dst_entry *dst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8187391c)
Location: include/net/dst.h:137
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff81898a5a)
Location: include/net/dst.h:137
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8189f7a5)
Location: include/net/dst.h:137
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff818a7c24)
Location: include/net/dst.h:137
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff818a7c24-ffffffff818a7c4a: dst_metrics_write_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 *dst_metrics_write_ptr(struct dst_entry *dst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f4284)
Location: include/net/dst.h:139
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff8191a58a)
Location: include/net/dst.h:139
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81921e4a)
Location: include/net/dst.h:139
Inline: True
```
```
In net/ipv6/ndisc.c (ffffffff8192a6d4)
Location: include/net/dst.h:139
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff8192a6d4-ffffffff8192a6ff: dst_metrics_write_ptr (STB_LOCAL)
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
Location: include/net/dst.h:122
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff81972b9d)
Location: include/net/dst.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff81982571)
Location: include/net/dst.h:122
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819a853d)
Location: include/net/dst.h:122
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:rt6_mtu_change_route
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff819ec425)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a1492d)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff81a2341d)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a4b51d)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
Location: include/net/dst.h:110
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81b48c33)
Location: include/net/dst.h:110
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
Location: include/net/dst.h:110
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81b57848)
Location: include/net/dst.h:110
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81b45424)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81c0c564)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
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
Location: include/net/dst.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81da746c)
Location: include/net/dst.h:112
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
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
Location: include/net/dst.h:112
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:dst_copy_metrics
```
```
In net/ipv6/route.c (ffffffff81f76a9c)
Location: include/net/dst.h:112
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
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
Location: include/net/dst.h:126
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:dst_copy_metrics
```
```
In net/ipv6/route.c (ffffffff81fd6acf)
Location: include/net/dst.h:126
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:dst_copy_metrics
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
Location: include/net/dst.h:126
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:dst_copy_metrics
```
```
In net/ipv6/route.c (ffffffff820a4449)
Location: include/net/dst.h:126
Inline: True
Inline callers:
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:dst_copy_metrics
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
In net/xfrm/xfrm_policy.c (ffff800010ce0474)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffff800010d11a84)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (c0de99dc)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (c0e14eb8)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (c000000000e0268c)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (c000000000e3b5b8)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffe00082f25c)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffe00085644c)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff819c2aad)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819eabad)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:tnl_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197f89d)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819a796d)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff81a2d52d)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a5562d)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff81a38cc3)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a6162d)
Location: include/net/dst.h:111
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:fib6_nh_mtu_change
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:rt6_do_update_pmtu
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_blackhole_route
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
