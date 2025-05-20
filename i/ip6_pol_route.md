# Function: <code>ip6_pol_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff817d58a0)
Location: net/ipv6/route.c:1040
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/route.c:ip6_pol_route_output
```
**Symbols:**

```
ffffffff817d58a0-ffffffff817d5e96: ip6_pol_route.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81843d00)
Location: net/ipv6/route.c:1045
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
```
**Symbols:**

```
ffffffff81843d00-ffffffff81844458: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81875a70)
Location: net/ipv6/route.c:1048
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
```
**Symbols:**

```
ffffffff81875a70-ffffffff818761c8: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189afe0)
Location: net/ipv6/route.c:1070
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
```
**Symbols:**

```
ffffffff8189afe0-ffffffff8189b860: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191db40)
Location: net/ipv6/route.c:1679
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:lookup_nexthop
```
**Symbols:**

```
ffffffff8191db40-ffffffff8191e4d4: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819764c0)
Location: net/ipv6/route.c:1850
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819764c0-ffffffff81976847: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ac0a0)
Location: net/ipv6/route.c:1841
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819ac0a0-ffffffff819ac427: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a19b70)
Location: net/ipv6/route.c:2182
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a19b70-ffffffff81a19e5f: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a507e0)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a507e0-ffffffff81a50acf: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b47bd0)
Location: net/ipv6/route.c:2210
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b47bd0-ffffffff81b47eb1: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b567a0)
Location: net/ipv6/route.c:2193
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b567a0-ffffffff81b56a78: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b443b0)
Location: net/ipv6/route.c:2200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b443b0-ffffffff81b44614: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0b310)
Location: net/ipv6/route.c:2203
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81c0b310-ffffffff81c0b711: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da6100)
Location: net/ipv6/route.c:2200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81da6100-ffffffff81da6522: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f75670)
Location: net/ipv6/route.c:2200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81f75670-ffffffff81f75a92: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd5710)
Location: net/ipv6/route.c:2199
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81fd5710-ffffffff81fd5b30: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a3070)
Location: net/ipv6/route.c:2201
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff820a3070-ffffffff820a34b4: ip6_pol_route (STB_GLOBAL)
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
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d14718)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffff800010d14718-ffff800010d14a14: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1a36c)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
c0e1a36c-c0e1a694: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e41410)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
c000000000e41410-c000000000e417d0: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000859f54)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffe000859f54-ffffffe00085a1f4: ip6_pol_route (STB_GLOBAL)
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
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819efe70)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819efe70-ffffffff819f015f: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819acc30)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819acc30-ffffffff819acf1f: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5a8f0)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a5a8f0-ffffffff81a5abdf: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route(struct net *net, struct fib6_table *table, int oif, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a66b70)
Location: net/ipv6/route.c:2188
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_pol_route_output
  - net/ipv6/route.c:ip6_pol_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a66b70-ffffffff81a66e91: ip6_pol_route (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff *skb</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, table, oif, fl6, flags</code> ➡️ <code>net, table, oif, fl6, skb, flags</code>
</li>
</ul>
</details>
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
