# Function: <code>fib_multipath_hash</code>

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
In net/ipv4/route.c (ffffffff81755971)
Location: include/net/ip_fib.h:327
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8178e1d8)
Location: include/net/ip_fib.h:327
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
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
In net/ipv4/route.c (ffffffff817c1b21)
Location: include/net/ip_fib.h:328
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff817fb7d5)
Location: include/net/ip_fib.h:328
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
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
In net/ipv4/route.c (ffffffff817f2111)
Location: include/net/ip_fib.h:369
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/icmp.c (ffffffff8182c6a2)
Location: include/net/ip_fib.h:369
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fib_multipath_hash(const struct fib_info *fi, const struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8180fae0)
Location: net/ipv4/route.c:1793
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8180fae0-ffffffff8180fd95: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fib_multipath_hash(const struct fib_info *fi, const struct flowi4 *fl4, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188f010)
Location: net/ipv4/route.c:1806
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8188f010-ffffffff8188f2d1: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e4780)
Location: net/ipv4/route.c:1826
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff818e4780-ffffffff818e4a37: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819116b0)
Location: net/ipv4/route.c:1823
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff819116b0-ffffffff81911930: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81973d10)
Location: net/ipv4/route.c:1914
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81973d10-ffffffff81974095: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819aa730)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff819aa730-ffffffff819aaab5: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a94a70)
Location: net/ipv4/route.c:1917
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81a94a70-ffffffff81a94ded: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9ea70)
Location: net/ipv4/route.c:1923
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81a9ea70-ffffffff81a9eded: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a899d0)
Location: net/ipv4/route.c:1911
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81a899d0-ffffffff81a89d4b: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b44560)
Location: net/ipv4/route.c:2022
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81b44560-ffffffff81b44bd3: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd11e0)
Location: net/ipv4/route.c:2044
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81cd11e0-ffffffff81cd18d8: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e91710)
Location: net/ipv4/route.c:2039
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81e91710-ffffffff81e91e08: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eefe90)
Location: net/ipv4/route.c:2037
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81eefe90-ffffffff81ef0583: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb3fe0)
Location: net/ipv4/route.c:2039
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81fb3fe0-ffffffff81fb46d3: fib_multipath_hash (STB_GLOBAL)
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
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5ab08)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffff800010c5ab08-ffff800010c5ae54: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d69fcc)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
c0d69fcc-c0d6a334: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5c710)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
c000000000d5c710-c000000000d5cb84: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c3ec6)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffe0007c3ec6-ffffffe0007c422e: fib_multipath_hash (STB_GLOBAL)
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
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194a5a0)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8194a5a0-ffffffff8194a925: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81904090)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81904090-ffffffff81904415: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b4d70)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff819b4d70-ffffffff819b50f5: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_multipath_hash(const struct net *net, const struct flowi4 *fl4, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819be4b0)
Location: net/ipv4/route.c:1918
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff819be4b0-ffffffff819be835: fib_multipath_hash (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct net *net</code>
</li>
<li>
<b>Param added. </b>
<code>struct flow_keys *flkeys</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fib_info *fi</code>
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
