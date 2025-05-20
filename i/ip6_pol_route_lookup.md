# Function: <code>ip6_pol_route_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d5010)
Location: net/ipv6/route.c:847
Inline: False
```
**Symbols:**

```
ffffffff817d5010-ffffffff817d528f: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81843530)
Location: net/ipv6/route.c:849
Inline: False
```
**Symbols:**

```
ffffffff81843530-ffffffff8184381b: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818752a0)
Location: net/ipv6/route.c:852
Inline: False
```
**Symbols:**

```
ffffffff818752a0-ffffffff8187558b: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189a0f0)
Location: net/ipv6/route.c:871
Inline: False
```
**Symbols:**

```
ffffffff8189a0f0-ffffffff8189a3c4: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191d230)
Location: net/ipv6/route.c:918
Inline: False
```
**Symbols:**

```
ffffffff8191d230-ffffffff8191d512: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81976190)
Location: net/ipv6/route.c:1053
Inline: False
```
**Symbols:**

```
ffffffff81976190-ffffffff819764b1: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819abdb0)
Location: net/ipv6/route.c:1060
Inline: False
```
**Symbols:**

```
ffffffff819abdb0-ffffffff819ac093: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:1206
Inline: False
```
**Symbols:**

```
ffffffff81a195c0-ffffffff81a19b6a: ip6_pol_route_lookup (STB_LOCAL)
ffffffff81a1d2c8-ffffffff81a1d2d2: ip6_pol_route_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a50220)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
ffffffff81a50220-ffffffff81a507d1: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b479c0)
Location: net/ipv6/route.c:1213
Inline: False
```
**Symbols:**

```
ffffffff81b479c0-ffffffff81b47bc3: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b565a0)
Location: net/ipv6/route.c:1196
Inline: False
Direct callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
**Symbols:**

```
ffffffff81b565a0-ffffffff81b56796: ip6_pol_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b441b0)
Location: net/ipv6/route.c:1199
Inline: False
Direct callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
**Symbols:**

```
ffffffff81b441b0-ffffffff81b443a6: ip6_pol_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0b110)
Location: net/ipv6/route.c:1199
Inline: False
Direct callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
**Symbols:**

```
ffffffff81c0b110-ffffffff81c0b306: ip6_pol_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da5ed0)
Location: net/ipv6/route.c:1202
Inline: False
Direct callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
**Symbols:**

```
ffffffff81da5ed0-ffffffff81da60fc: ip6_pol_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f75430)
Location: net/ipv6/route.c:1202
Inline: False
Direct callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
**Symbols:**

```
ffffffff81f75430-ffffffff81f7565c: ip6_pol_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd54c0)
Location: net/ipv6/route.c:1201
Inline: False
Direct callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
**Symbols:**

```
ffffffff81fd54c0-ffffffff81fd56f1: ip6_pol_route_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a2e20)
Location: net/ipv6/route.c:1203
Inline: False
Direct callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
  - net/ipv6/fib6_rules.c:fib6_rule_lookup
```
**Symbols:**

```
ffffffff820a2e20-ffffffff820a3051: ip6_pol_route_lookup (STB_GLOBAL)
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
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d14198)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
ffff800010d14198-ffff800010d14718: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e19d24)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
c0e19d24-c0e1a36c: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e40d20)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
c000000000e40d20-c000000000e41404: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000859b06)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
ffffffe000859b06-ffffffe000859f54: ip6_pol_route_lookup (STB_LOCAL)
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
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ef8b0)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
ffffffff819ef8b0-ffffffff819efe61: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ac670)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
ffffffff819ac670-ffffffff819acc21: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5a330)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
ffffffff81a5a330-ffffffff81a5a8e1: ip6_pol_route_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rt6_info *ip6_pol_route_lookup(struct net *net, struct fib6_table *table, struct flowi6 *fl6, const struct sk_buff *skb, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a66590)
Location: net/ipv6/route.c:1212
Inline: False
```
**Symbols:**

```
ffffffff81a66590-ffffffff81a66b6d: ip6_pol_route_lookup (STB_LOCAL)
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
<code>net, table, fl6, flags</code> ➡️ <code>net, table, fl6, skb, flags</code>
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
