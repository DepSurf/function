# Function: <code>dst_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81723e70)
Location: net/core/dst.c:248
Inline: False
Direct callers:
  - net/core/dst.c:dst_gc_task
  - net/core/dst.c:dst_destroy_rcu
  - net/ipv4/route.c:dst_rcu_free
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/ip6_fib.c:dst_rcu_free
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81723e70-ffffffff81723f5c: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8178d8c0)
Location: net/core/dst.c:248
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy_rcu
  - net/core/dst.c:dst_gc_task
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:dst_rcu_free
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:dst_rcu_free
```
**Symbols:**

```
ffffffff8178d8c0-ffffffff8178d9d3: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817bb190)
Location: net/core/dst.c:248
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy_rcu
  - net/core/dst.c:dst_gc_task
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:dst_rcu_free
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_flo_delete
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_ifdown
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:icmp6_dst_gc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_dst_alloc
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:dst_rcu_free
```
**Symbols:**

```
ffffffff817bb190-ffffffff817bb2a3: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817d9950)
Location: net/core/dst.c:117
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff817d9950-ffffffff817d9a08: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81854300)
Location: net/core/dst.c:117
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81854300-ffffffff818543af: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8189fa10)
Location: net/core/dst.c:115
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff8189fa10-ffffffff8189fac6: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff818c21a0)
Location: net/core/dst.c:115
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff818c21a0-ffffffff818c2255: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8190e900)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff8190e900-ffffffff8190e9b5: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81940f60)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81940f60-ffffffff81941015: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81a10b20)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81a10b20-ffffffff81a10be9: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81a10ed0)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81a10ed0-ffffffff81a10f9c: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff819f7d40)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff819f7d40-ffffffff819f7e0c: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81aa9970)
Location: net/core/dst.c:102
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81aa9970-ffffffff81aa9a3c: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81c21db0)
Location: net/core/dst.c:102
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81c21db0-ffffffff81c21e86: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81dd4300)
Location: net/core/dst.c:102
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81dd4300-ffffffff81dd43f6: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81e450a0)
Location: net/core/dst.c:99
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy_rcu
  - net/core/dst.c:dst_destroy
```
**Symbols:**

```
ffffffff81e450a0-ffffffff81e45204: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81f03d20)
Location: net/core/dst.c:99
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy_rcu
  - net/core/dst.c:dst_destroy
```
**Symbols:**

```
ffffffff81f03d20-ffffffff81f03e84: dst_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffff800010be0e00)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffff800010be0e00-ffff800010be0f04: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c0cfac6c)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
c0cfac6c-c0cfad94: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c000000000cc1720)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
c000000000cc1720-c000000000cc18ac: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffe000767012)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffe000767012-ffffffe0007670f4: dst_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff818e0f30)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff818e0f30-ffffffff818e0fe5: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8189ad70)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff8189ad70-ffffffff8189ae25: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81931f60)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81931f60-ffffffff81932015: dst_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *dst_destroy(struct dst_entry *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81953630)
Location: net/core/dst.c:103
Inline: False
Direct callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_destroy_rcu
```
**Symbols:**

```
ffffffff81953630-ffffffff819536e5: dst_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
