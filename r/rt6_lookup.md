# Function: <code>rt6_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d3420)
Location: net/ipv6/route.c:879
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff817d3420-ffffffff817d34c5: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81840f50)
Location: net/ipv6/route.c:884
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81840f50-ffffffff81840ff5: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81872c40)
Location: net/ipv6/route.c:887
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81872c40-ffffffff81872ce5: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81897850)
Location: net/ipv6/route.c:906
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81897850-ffffffff81897917: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81918af0)
Location: net/ipv6/route.c:969
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81918af0-ffffffff81918bb7: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819709d0)
Location: net/ipv6/route.c:1116
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819709d0-ffffffff81970a94: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6600)
Location: net/ipv6/route.c:1119
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819a6600-ffffffff819a66c7: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a12a30)
Location: net/ipv6/route.c:1269
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a12a30-ffffffff81a12aed: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49620)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a49620-ffffffff81a496dd: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40070)
Location: net/ipv6/route.c:1276
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b40070-ffffffff81b4012d: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4ed60)
Location: net/ipv6/route.c:1259
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b4ed60-ffffffff81b4ee1d: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3cb90)
Location: net/ipv6/route.c:1262
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81b3cb90-ffffffff81b3cc4d: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c03530)
Location: net/ipv6/route.c:1262
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81c03530-ffffffff81c035ed: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9d510)
Location: net/ipv6/route.c:1262
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81d9d510-ffffffff81d9d5ec: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6c520)
Location: net/ipv6/route.c:1262
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81f6c520-ffffffff81f6c5fc: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcc660)
Location: net/ipv6/route.c:1261
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81fcc660-ffffffff81fcc73c: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff82099e40)
Location: net/ipv6/route.c:1263
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rtnl
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff82099e40-ffffffff82099f1c: rt6_lookup (STB_GLOBAL)
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
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0ca58)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffff800010d0ca58-ffff800010d0cb40: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e12a34)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
c0e12a34-c0e12b28: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e37950)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
c000000000e37950-c000000000e37a90: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000853b02)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffe000853b02-ffffffe000853bd6: rt6_lookup (STB_GLOBAL)
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
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e8cb0)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819e8cb0-ffffffff819e8d6d: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a5a70)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff819a5a70-ffffffff819a5b2d: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53730)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a53730-ffffffff81a537ed: rt6_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rt6_info *rt6_lookup(struct net *net, const struct in6_addr *daddr, const struct in6_addr *saddr, int oif, const struct sk_buff *skb, int strict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5f720)
Location: net/ipv6/route.c:1275
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_sock_ac_join
  - net/ipv6/icmp.c:ip6_err_gen_icmpv6_unreach
  - net/ipv6/mcast.c:ip6_mc_find_dev_rcu
  - net/ipv6/mcast.c:__ipv6_sock_mc_join
```
**Symbols:**

```
ffffffff81a5f720-ffffffff81a5f7dd: rt6_lookup (STB_GLOBAL)
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
<code>net, daddr, saddr, oif, strict</code> ➡️ <code>net, daddr, saddr, oif, skb, strict</code>
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
