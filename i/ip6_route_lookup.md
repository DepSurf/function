# Function: <code>ip6_route_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d3400)
Location: net/ipv6/route.c:872
Inline: False
```
**Symbols:**

```
ffffffff817d3400-ffffffff817d3417: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81840f30)
Location: net/ipv6/route.c:877
Inline: False
```
**Symbols:**

```
ffffffff81840f30-ffffffff81840f47: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81872c20)
Location: net/ipv6/route.c:880
Inline: False
```
**Symbols:**

```
ffffffff81872c20-ffffffff81872c37: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818992d4)
Location: net/ipv6/route.c:899
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rtm_getroute
```
**Symbols:**

```
ffffffff81897830-ffffffff81897847: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81918ad0)
Location: net/ipv6/route.c:962
Inline: False
```
**Symbols:**

```
ffffffff81918ad0-ffffffff81918ae7: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81970740)
Location: net/ipv6/route.c:1109
Inline: False
```
**Symbols:**

```
ffffffff81970740-ffffffff81970757: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6370)
Location: net/ipv6/route.c:1112
Inline: False
```
**Symbols:**

```
ffffffff819a6370-ffffffff819a6387: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12990)
Location: net/ipv6/route.c:1262
Inline: False
```
**Symbols:**

```
ffffffff81a12990-ffffffff81a129a7: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49580)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
ffffffff81a49580-ffffffff81a49597: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3ffd0)
Location: net/ipv6/route.c:1269
Inline: False
```
**Symbols:**

```
ffffffff81b3ffd0-ffffffff81b3ffe7: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4ed40)
Location: net/ipv6/route.c:1252
Inline: False
```
**Symbols:**

```
ffffffff81b4ed40-ffffffff81b4ed57: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3cb70)
Location: net/ipv6/route.c:1255
Inline: False
```
**Symbols:**

```
ffffffff81b3cb70-ffffffff81b3cb87: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c03510)
Location: net/ipv6/route.c:1255
Inline: False
```
**Symbols:**

```
ffffffff81c03510-ffffffff81c03527: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9d4e0)
Location: net/ipv6/route.c:1255
Inline: False
```
**Symbols:**

```
ffffffff81d9d4e0-ffffffff81d9d506: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6c460)
Location: net/ipv6/route.c:1255
Inline: False
```
**Symbols:**

```
ffffffff81f6c460-ffffffff81f6c486: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcc5a0)
Location: net/ipv6/route.c:1254
Inline: False
```
**Symbols:**

```
ffffffff81fcc5a0-ffffffff81fcc5c6: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff82099d80)
Location: net/ipv6/route.c:1256
Inline: False
```
**Symbols:**

```
ffffffff82099d80-ffffffff82099da6: ip6_route_lookup (STB_GLOBAL)
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
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0c960)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
ffff800010d0c960-ffff800010d0c9b4: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e128d4)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
c0e128d4-c0e12904: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e37810)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
c000000000e37810-c000000000e3784c: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000853952)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
ffffffe000853952-ffffffe00085399c: ip6_route_lookup (STB_GLOBAL)
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
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e8c10)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
ffffffff819e8c10-ffffffff819e8c27: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a59d0)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
ffffffff819a59d0-ffffffff819a59e7: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53690)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
ffffffff81a53690-ffffffff81a536a7: ip6_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *ip6_route_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5f680)
Location: net/ipv6/route.c:1268
Inline: False
```
**Symbols:**

```
ffffffff81a5f680-ffffffff81a5f697: ip6_route_lookup (STB_GLOBAL)
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
<code>const struct sk_buff *skb</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, fl6, flags</code> ➡️ <code>net, fl6, skb, flags</code>
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
