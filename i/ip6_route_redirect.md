# Function: <code>ip6_route_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dst_entry *ip6_route_redirect(struct net *net, const struct flowi6 *fl6, const struct in6_addr *gateway);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d34d0)
Location: net/ipv6/route.c:1479
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_redirect
  - net/ipv6/route.c:ip6_redirect_no_header
```
**Symbols:**

```
ffffffff817d34d0-ffffffff817d3578: ip6_route_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dst_entry *ip6_route_redirect(struct net *net, const struct flowi6 *fl6, const struct in6_addr *gateway);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81841000)
Location: net/ipv6/route.c:1503
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81841000-ffffffff818410a8: ip6_route_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *ip6_route_redirect(struct net *net, const struct flowi6 *fl6, const struct in6_addr *gateway);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81872cf0)
Location: net/ipv6/route.c:1515
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81872cf0-ffffffff81872da1: ip6_route_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *ip6_route_redirect(struct net *net, const struct flowi6 *fl6, const struct in6_addr *gateway);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81897920)
Location: net/ipv6/route.c:1552
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81897920-ffffffff818979cd: ip6_route_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *ip6_route_redirect(struct net *net, const struct flowi6 *fl6, const struct in6_addr *gateway);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81918bc0)
Location: net/ipv6/route.c:2240
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81918bc0-ffffffff81918c75: ip6_route_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819717b0)
Location: net/ipv6/route.c:2508
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff819717b0-ffffffff81971863: ip6_route_redirect.isra.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819a7150)
Location: net/ipv6/route.c:2501
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff819a7150-ffffffff819a71fa: ip6_route_redirect.isra.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a13760)
Location: net/ipv6/route.c:2973
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81a13760-ffffffff81a13813: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4a350)
Location: net/ipv6/route.c:2983
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81a4a350-ffffffff81a4a403: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b41050)
Location: net/ipv6/route.c:3007
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81b41050-ffffffff81b41101: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4fb10)
Location: net/ipv6/route.c:2991
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81b4fb10-ffffffff81b4fbc1: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3d720)
Location: net/ipv6/route.c:3000
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81b3d720-ffffffff81b3d7d4: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81c03f60)
Location: net/ipv6/route.c:3130
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81c03f60-ffffffff81c04014: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9e1f0)
Location: net/ipv6/route.c:3120
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81d9e1f0-ffffffff81d9e2bc: ip6_route_redirect.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6d090)
Location: net/ipv6/route.c:3120
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81f6d090-ffffffff81f6d15c: ip6_route_redirect.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcd070)
Location: net/ipv6/route.c:3120
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81fcd070-ffffffff81fcd13c: ip6_route_redirect.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff8209a890)
Location: net/ipv6/route.c:3122
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff8209a890-ffffffff8209a953: ip6_route_redirect.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffff800010d0d498)
Location: net/ipv6/route.c:2983
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffff800010d0d498-ffff800010d0d550: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *ip6_route_redirect(struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, const struct in6_addr *gateway);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e12904)
Location: net/ipv6/route.c:2983
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
c0e12904-c0e12998: ip6_route_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (c000000000e39010)
Location: net/ipv6/route.c:2983
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
c000000000e39010-c000000000e390cc: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *ip6_route_redirect(struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, const struct in6_addr *gateway);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085399c)
Location: net/ipv6/route.c:2983
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffe00085399c-ffffffe000853a70: ip6_route_redirect (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819e99e0)
Location: net/ipv6/route.c:2983
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff819e99e0-ffffffff819e9a93: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819a67a0)
Location: net/ipv6/route.c:2983
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff819a67a0-ffffffff819a6853: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a54460)
Location: net/ipv6/route.c:2983
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81a54460-ffffffff81a54513: ip6_route_redirect.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81a60450)
Location: net/ipv6/route.c:2983
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_redirect_no_header
  - net/ipv6/route.c:ip6_redirect
```
**Symbols:**

```
ffffffff81a60450-ffffffff81a60503: ip6_route_redirect.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
