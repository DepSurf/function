# Function: <code>dst_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817238a0)
Location: net/core/dst.c:200
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_dst_alloc
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/ipv6/route.c:__ip6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
```
**Symbols:**

```
ffffffff817238a0-ffffffff81723935: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8178d300)
Location: net/core/dst.c:200
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:__ip6_dst_alloc
```
**Symbols:**

```
ffffffff8178d300-ffffffff8178d395: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817babd0)
Location: net/core/dst.c:200
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:__ip6_dst_alloc
```
**Symbols:**

```
ffffffff817babd0-ffffffff817bac65: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817d9c10)
Location: net/core/dst.c:97
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:__ip6_dst_alloc
```
**Symbols:**

```
ffffffff817d9c10-ffffffff817d9c9a: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81854240)
Location: net/core/dst.c:97
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:__ip6_dst_alloc
```
**Symbols:**

```
ffffffff81854240-ffffffff818542d0: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8189f940)
Location: net/core/dst.c:95
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff8189f940-ffffffff8189f9d0: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff818c2480)
Location: net/core/dst.c:95
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff818c2480-ffffffff818c2510: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst.c (ffffffff8190ec83)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff8190ecde-ffffffff8190ecf1: dst_alloc.cold (STB_LOCAL)
ffffffff8190ebf0-ffffffff8190eca2: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst.c (ffffffff819412f3)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff8194134e-ffffffff81941361: dst_alloc.cold (STB_LOCAL)
ffffffff81941260-ffffffff81941312: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:79
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81a10fc8-ffffffff81a10fdc: dst_alloc.cold (STB_LOCAL)
ffffffff81a10e30-ffffffff81a10f92: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:79
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81c315a2-ffffffff81c315b6: dst_alloc.cold (STB_LOCAL)
ffffffff81a111e0-ffffffff81a11342: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:79
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81c238ab-ffffffff81c238bf: dst_alloc.cold (STB_LOCAL)
ffffffff819f8050-ffffffff819f81af: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:78
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81d369d0-ffffffff81d369e4: dst_alloc.cold (STB_LOCAL)
ffffffff81aa9cc0-ffffffff81aa9e1f: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dst.c (0)
Location: net/core/dst.c:78
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81f032b4-ffffffff81f032c5: dst_alloc.cold (STB_LOCAL)
ffffffff81c22170-ffffffff81c222cb: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81dd4520)
Location: net/core/dst.c:78
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81dd4520-ffffffff81dd468a: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81e452e0)
Location: net/core/dst.c:79
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
```
**Symbols:**

```
ffffffff81e452e0-ffffffff81e4542e: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81f03f60)
Location: net/core/dst.c:79
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
```
**Symbols:**

```
ffffffff81f03f60-ffffffff81f040b2: dst_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffff800010be0c50)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffff800010be0c50-ffff800010be0d24: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c0cfb074)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
c0cfb074-c0cfb174: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c000000000cc1e40)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
c000000000cc1e40-c000000000cc1f60: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffe0007672f6)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffe0007672f6-ffffffe0007673a6: dst_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst.c (ffffffff818e12c3)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff818e131e-ffffffff818e1331: dst_alloc.cold (STB_LOCAL)
ffffffff818e1230-ffffffff818e12e2: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst.c (ffffffff8189b103)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff8189b15e-ffffffff8189b171: dst_alloc.cold (STB_LOCAL)
ffffffff8189b070-ffffffff8189b122: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst.c (ffffffff819322f3)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff8193234e-ffffffff81932361: dst_alloc.cold (STB_LOCAL)
ffffffff81932260-ffffffff81932312: dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *dst_alloc(struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dst.c (ffffffff819539c3)
Location: net/core/dst.c:79
Inline: True
Direct callers:
  - net/ipv4/route.c:ipv4_blackhole_route
  - net/ipv4/route.c:rt_dst_clone
  - net/ipv4/route.c:rt_dst_alloc
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/ipv6/route.c:ip6_blackhole_route
  - net/ipv6/route.c:ip6_dst_alloc
```
**Symbols:**

```
ffffffff81953a1e-ffffffff81953a31: dst_alloc.cold (STB_LOCAL)
ffffffff81953930-ffffffff819539e2: dst_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int initial_ref</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, dev, initial_ref, initial_obsolete, flags</code> ➡️ <code>ops, dev, initial_obsolete, flags</code>
</li>
</ul>
</details>
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
