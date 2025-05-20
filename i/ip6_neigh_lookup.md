# Function: <code>ip6_neigh_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d5370)
Location: net/ipv6/route.c:203
Inline: False
```
**Symbols:**

```
ffffffff817d5370-ffffffff817d54e7: ip6_neigh_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81843280)
Location: net/ipv6/route.c:204
Inline: False
```
**Symbols:**

```
ffffffff81843280-ffffffff818433f5: ip6_neigh_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81874ff0)
Location: net/ipv6/route.c:206
Inline: False
```
**Symbols:**

```
ffffffff81874ff0-ffffffff81875165: ip6_neigh_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818997a0)
Location: net/ipv6/route.c:211
Inline: False
```
**Symbols:**

```
ffffffff818997a0-ffffffff81899907: ip6_neigh_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct dst_entry *dst, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191abf0)
Location: net/ipv6/route.c:217
Inline: False
```
**Symbols:**

```
ffffffff8191abf0-ffffffff8191ad86: ip6_neigh_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81975560)
Location: net/ipv6/route.c:202
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81975560-ffffffff819756ec: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab1a0)
Location: net/ipv6/route.c:202
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819ab1a0-ffffffff819ab33b: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a18b30)
Location: net/ipv6/route.c:199
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a18b30-ffffffff81a18ca7: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4f790)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a4f790-ffffffff81a4f907: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b46ed0)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b46ed0-ffffffff81b4704e: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b55ad0)
Location: net/ipv6/route.c:201
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b55ad0-ffffffff81b55c4e: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b436f0)
Location: net/ipv6/route.c:204
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81b436f0-ffffffff81b43864: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:204
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81d3ffd4-ffffffff81d3fff3: ip6_neigh_lookup.cold (STB_LOCAL)
ffffffff81c0a250-ffffffff81c0a3e1: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:209
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81f0c94e-ffffffff81f0c96c: ip6_neigh_lookup.cold (STB_LOCAL)
ffffffff81da4f10-ffffffff81da50c5: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:209
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff820b3f9f-ffffffff820b3fbd: ip6_neigh_lookup.cold (STB_LOCAL)
ffffffff81f743f0-ffffffff81f745a5: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:209
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff82135066-ffffffff82135084: ip6_neigh_lookup.cold (STB_LOCAL)
ffffffff81fd44d0-ffffffff81fd464d: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:209
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff82216b2a-ffffffff82216b48: ip6_neigh_lookup.cold (STB_LOCAL)
ffffffff820a1de0-ffffffff820a1f5d: ip6_neigh_lookup (STB_GLOBAL)
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
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d13668)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffff800010d13668-ffff800010d137dc: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e19238)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c0e19238-c0e193b4: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3ff00)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
c000000000e3ff00-c000000000e40128: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008591d6)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffe0008591d6-ffffffe000859344: ip6_neigh_lookup (STB_GLOBAL)
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
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eee20)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819eee20-ffffffff819eef97: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819abbe0)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff819abbe0-ffffffff819abd57: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a598a0)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a598a0-ffffffff81a59a17: ip6_neigh_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct neighbour *ip6_neigh_lookup(const struct in6_addr *gw, struct net_device *dev, struct sk_buff *skb, const void *daddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a65ae0)
Location: net/ipv6/route.c:200
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/route.c:ip6_dst_neigh_lookup
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
```
**Symbols:**

```
ffffffff81a65ae0-ffffffff81a65c57: ip6_neigh_lookup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct in6_addr *gw</code>
</li>
<li>
<b>Param added. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct dst_entry *dst</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst, skb, daddr</code> ➡️ <code>gw, dev, skb, daddr</code>
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
