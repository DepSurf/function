# Function: <code>dst_copy_metrics</code>

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
Location: include/net/dst.h:158
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
```
```
In net/ipv6/route.c (ffffffff817d71c7)
Location: include/net/dst.h:158
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff818226cd)
Location: include/net/dst.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff818458dc)
Location: include/net/dst.h:155
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff81853fcd)
Location: include/net/dst.h:155
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff8187763c)
Location: include/net/dst.h:155
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff81877aa3)
Location: include/net/dst.h:159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff8189c929)
Location: include/net/dst.h:159
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff818f85a1)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff8191f57a)
Location: include/net/dst.h:161
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
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
In net/xfrm/xfrm_policy.c (ffffffff8194f058)
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/ipv6/route.c (ffffffff81977686)
Location: include/net/dst.h:144
Inline: True
Inline callers:
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
Location: include/net/dst.h:144
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819ad286)
Location: include/net/dst.h:144
Inline: True
Inline callers:
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a1a406)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a51076)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
In net/xfrm/xfrm_policy.c (ffffffff81b11315)
Location: include/net/dst.h:132
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81b4875e)
Location: include/net/dst.h:132
Inline: True
Inline callers:
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
In net/xfrm/xfrm_policy.c (ffffffff81b1fbb6)
Location: include/net/dst.h:132
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81b5733e)
Location: include/net/dst.h:132
Inline: True
Inline callers:
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
In net/xfrm/xfrm_policy.c (ffffffff81b0da98)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81b44f2e)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
In net/xfrm/xfrm_policy.c (ffffffff81bd0662)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81c0c06e)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
In net/xfrm/xfrm_policy.c (ffffffff81d66b12)
Location: include/net/dst.h:134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81da6ee6)
Location: include/net/dst.h:134
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void dst_copy_metrics(struct dst_entry *dest, const struct dst_entry *src);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f2f210)
Location: include/net/dst.h:134
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81f764d6)
Location: include/net/dst.h:134
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
```
**Symbols:**

```
ffffffff81f2f210-ffffffff81f2f2a2: dst_copy_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void dst_copy_metrics(struct dst_entry *dest, const struct dst_entry *src);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f8fa10)
Location: include/net/dst.h:148
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81fccd40)
Location: include/net/dst.h:148
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
```
**Symbols:**

```
ffffffff81f8fa10-ffffffff81f8faa2: dst_copy_metrics (STB_LOCAL)
ffffffff81fccd40-ffffffff81fccdd2: dst_copy_metrics (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void dst_copy_metrics(struct dst_entry *dest, const struct dst_entry *src);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8205d770)
Location: include/net/dst.h:148
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff8209a550)
Location: include/net/dst.h:148
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_blackhole_route
```
**Symbols:**

```
ffffffff8205d770-ffffffff8205d802: dst_copy_metrics (STB_LOCAL)
ffffffff8209a550-ffffffff8209a5e2: dst_copy_metrics (STB_LOCAL)
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffff800010d15020)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (c0e1ac8c)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (c000000000e41efc)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffe00085a71a)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819f0706)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
In net/xfrm/xfrm_policy.c (ffffffff8197f89d)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff819ad4c6)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a5b186)
Location: include/net/dst.h:133
Inline: True
Inline callers:
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
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/ipv6/route.c (ffffffff81a67466)
Location: include/net/dst.h:133
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_blackhole_route
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
