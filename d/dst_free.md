# Function: <code>dst_free</code>

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
In net/ipv4/route.c (ffffffff81754650)
Location: include/net/dst.h:414
Inline: True
Inline callers:
  - net/ipv4/route.c:dst_rcu_free
  - net/ipv4/route.c:ipv4_blackhole_route
```
```
In net/ipv4/fib_semantics.c (ffffffff8179c1ec)
Location: include/net/dst.h:414
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1c75)
Location: include/net/dst.h:414
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
```
```
In net/ipv6/route.c (ffffffff817d6337)
Location: include/net/dst.h:414
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:rt6_ifdown
```
```
In net/ipv6/ip6_fib.c (ffffffff817da8d0)
Location: include/net/dst.h:414
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:dst_rcu_free
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
In net/ipv4/route.c (ffffffff817c3e00)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:dst_rcu_free
```
```
In net/ipv4/fib_semantics.c (ffffffff81809d6d)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/xfrm/xfrm_policy.c (ffffffff8182245a)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete
```
```
In net/ipv6/route.c (ffffffff81844ef8)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:ip6_blackhole_route
```
```
In net/ipv6/ip6_fib.c (ffffffff81849799)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:dst_rcu_free
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
In net/ipv4/route.c (ffffffff817f3920)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:dst_rcu_free
```
```
In net/ipv4/fib_semantics.c (ffffffff8183aeed)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81853d5a)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete
```
```
In net/ipv6/route.c (ffffffff81876c68)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:ip6_blackhole_route
```
```
In net/ipv6/ip6_fib.c (ffffffff8187b614)
Location: include/net/dst.h:423
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:dst_rcu_free
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
