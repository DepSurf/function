# Function: <code>fib6_rule_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff817fe760)
Location: net/ipv6/fib6_rules.c:32
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_redirect
```
**Symbols:**

```
ffffffff817fe760-ffffffff817fe816: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff8186e0f0)
Location: net/ipv6/fib6_rules.c:32
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_redirect
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff8186e0f0-ffffffff8186e1a6: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff818a0ed0)
Location: net/ipv6/fib6_rules.c:32
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_redirect
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff818a0ed0-ffffffff818a0f9f: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff818c7540)
Location: net/ipv6/fib6_rules.c:32
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_redirect
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
```
**Symbols:**

```
ffffffff818c7540-ffffffff818c761a: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff8194aaa0)
Location: net/ipv6/fib6_rules.c:63
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_redirect
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff8194aaa0-ffffffff8194abf5: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff819a3d70)
Location: net/ipv6/fib6_rules.c:96
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff819a3d70-ffffffff819a3ec4: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff819da880)
Location: net/ipv6/fib6_rules.c:96
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff819da880-ffffffff819da9d4: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81a4968d-ffffffff81a4969f: fib6_rule_lookup.cold (STB_LOCAL)
ffffffff81a49460-ffffffff81a49648: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a80060)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81a80060-ffffffff81a8023b: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81b7aca0)
Location: net/ipv6/fib6_rules.c:90
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81b7aca0-ffffffff81b7ae7e: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81b89c50)
Location: net/ipv6/fib6_rules.c:91
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81b89c50-ffffffff81b89ebc: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81b78aa0)
Location: net/ipv6/fib6_rules.c:91
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81b78aa0-ffffffff81b78d08: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:91
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81d41516-ffffffff81d41532: fib6_rule_lookup.cold (STB_LOCAL)
ffffffff81c43600-ffffffff81c43894: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:92
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81f0de89-ffffffff81f0dea6: fib6_rule_lookup.cold (STB_LOCAL)
ffffffff81de2330-ffffffff81de25f9: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:92
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff820b5231-ffffffff820b524e: fib6_rule_lookup.cold (STB_LOCAL)
ffffffff81fb48a0-ffffffff81fb4b69: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:92
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff821360eb-ffffffff82136108: fib6_rule_lookup.cold (STB_LOCAL)
ffffffff82015020-ffffffff820152ca: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/fib6_rules.c (0)
Location: net/ipv6/fib6_rules.c:92
Inline: False
Direct callers:
  - net/ipv6/route.c:inet6_rtm_getroute
  - net/ipv6/route.c:ip6_route_output_flags
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff82217d07-ffffffff82217d24: fib6_rule_lookup.cold (STB_LOCAL)
ffffffff820e4160-ffffffff820e440a: fib6_rule_lookup (STB_GLOBAL)
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
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffff800010d4b6f8)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffff800010d4b6f8-ffff800010d4b908: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (c0e4c9fc)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_redirect
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
c0e4c9fc-c0e4cc18: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (c000000000e819d0)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
c000000000e819d0-c000000000e81c50: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffe0008846ac)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_redirect
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffe0008846ac-ffffffe00088481c: fib6_rule_lookup (STB_GLOBAL)
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
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a1f6f0)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81a1f6f0-ffffffff81a1f8cb: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff819dc4b0)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff819dc4b0-ffffffff819dc68b: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a8a170)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81a8a170-ffffffff81a8a34b: fib6_rule_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dst_entry *fib6_rule_lookup(struct net *net, struct flowi6 *fl6, const struct sk_buff *skb, int flags, pol_lookup_t lookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/fib6_rules.c (ffffffff81a96dd0)
Location: net/ipv6/fib6_rules.c:89
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_output_flags_noref
  - net/ipv6/route.c:ip6_route_input_lookup
  - net/ipv6/route.c:rt6_lookup
  - net/ipv6/route.c:ip6_route_lookup
```
**Symbols:**

```
ffffffff81a96dd0-ffffffff81a96fab: fib6_rule_lookup (STB_GLOBAL)
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
<code>net, fl6, flags, lookup</code> ➡️ <code>net, fl6, skb, flags, lookup</code>
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
