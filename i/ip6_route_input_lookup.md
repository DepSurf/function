# Function: <code>ip6_route_input_lookup</code>

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
In net/ipv6/route.c (ffffffff817d4850)
Location: net/ipv6/route.c:1139
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff817d4850-ffffffff817d48a3: ip6_route_input_lookup.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81841e40)
Location: net/ipv6/route.c:1150
Inline: True
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
**Symbols:**

```
ffffffff81841e40-ffffffff81841e93: ip6_route_input_lookup.isra.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81873170)
Location: net/ipv6/route.c:1154
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
**Symbols:**

```
ffffffff81873170-ffffffff818731c7: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81897b40)
Location: net/ipv6/route.c:1179
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
```
**Symbols:**

```
ffffffff81897b40-ffffffff81897b97: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81918df0)
Location: net/ipv6/route.c:1807
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:lookup_nexthop
```
**Symbols:**

```
ffffffff81918df0-ffffffff81918e47: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81970960)
Location: net/ipv6/route.c:1937
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81970960-ffffffff819709c1: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6590)
Location: net/ipv6/route.c:1928
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819a6590-ffffffff819a65f1: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12d30)
Location: net/ipv6/route.c:2261
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a12d30-ffffffff81a12d90: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49920)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a49920-ffffffff81a49980: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b45b96)
Location: net/ipv6/route.c:2289
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
Direct callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b40360-ffffffff81b403c0: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b5453c)
Location: net/ipv6/route.c:2272
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
Direct callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b4ee20-ffffffff81b4ee80: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b41ca2)
Location: net/ipv6/route.c:2279
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
Direct callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81b3cc50-ffffffff81b3ccb0: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c099d2)
Location: net/ipv6/route.c:2282
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
Direct callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81c035f0-ffffffff81c03650: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da4ba3)
Location: net/ipv6/route.c:2278
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
Direct callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81d9d5f0-ffffffff81d9d660: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f74053)
Location: net/ipv6/route.c:2278
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
Direct callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81f6c4a0-ffffffff81f6c510: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd4133)
Location: net/ipv6/route.c:2277
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
Direct callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff81fcc5e0-ffffffff81fcc650: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a1a45)
Location: net/ipv6/route.c:2279
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
Direct callers:
  - net/ipv6/xfrm6_protocol.c:xfrm6_rcv_encap
  - net/ipv6/seg6_local.c:seg6_lookup_any_nexthop
```
**Symbols:**

```
ffffffff82099dc0-ffffffff82099e30: ip6_route_input_lookup (STB_GLOBAL)
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
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0cb40)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffff800010d0cb40-ffff800010d0cbc4: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e12f28)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
c0e12f28-c0e12fa0: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e380d0)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
c000000000e380d0-c000000000e38178: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000854086)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffe000854086-ffffffe0008540f8: ip6_route_input_lookup (STB_GLOBAL)
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
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e8fb0)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819e8fb0-ffffffff819e9010: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5d70)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff819a5d70-ffffffff819a5dd0: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53a30)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a53a30-ffffffff81a53a90: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *ip6_route_input_lookup(struct net *net, struct net_device *dev, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5fa20)
Location: net/ipv6/route.c:2267
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/seg6_local.c:seg6_lookup_nexthop
```
**Symbols:**

```
ffffffff81a5fa20-ffffffff81a5fa80: ip6_route_input_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>net, dev, fl6, flags</code> ➡️ <code>net, dev, fl6, skb, flags</code>
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
