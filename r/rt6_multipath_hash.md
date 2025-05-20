# Function: <code>rt6_multipath_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 rt6_multipath_hash(const struct flowi6 *fl6, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff8191f4ad)
Location: net/ipv6/route.c:1854
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:rt6_multipath_select
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff8191a710-ffffffff8191a754: rt6_multipath_hash.part.61 (STB_LOCAL)
ffffffff8191f340-ffffffff8191f39a: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81975cf0)
Location: net/ipv6/route.c:1999
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_multipath_select
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81975cf0-ffffffff819760b4: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab940)
Location: net/ipv6/route.c:1990
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_multipath_select
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff819ab940-ffffffff819abcde: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a190f0)
Location: net/ipv6/route.c:2323
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a190f0-ffffffff81a19409: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4fd50)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a4fd50-ffffffff81a50069: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b474e0)
Location: net/ipv6/route.c:2348
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81b474e0-ffffffff81b477f2: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b560c0)
Location: net/ipv6/route.c:2331
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81b560c0-ffffffff81b563d2: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43cd0)
Location: net/ipv6/route.c:2338
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81b43cd0-ffffffff81b43fe3: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c0a850)
Location: net/ipv6/route.c:2460
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81c0a850-ffffffff81c0aef5: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da5580)
Location: net/ipv6/route.c:2456
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81da5580-ffffffff81da5c96: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f74ac0)
Location: net/ipv6/route.c:2456
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81f74ac0-ffffffff81f751d6: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd4b60)
Location: net/ipv6/route.c:2455
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81fd4b60-ffffffff81fd5270: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a2470)
Location: net/ipv6/route.c:2457
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff820a2470-ffffffff820a2b80: rt6_multipath_hash (STB_GLOBAL)
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
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d13d08)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffff800010d13d08-ffff800010d13fd0: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e19870)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
c0e19870-c0e19b6c: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e406b0)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
c000000000e406b0-c000000000e40a8c: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008596c8)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffe0008596c8-ffffffe000859996: rt6_multipath_hash (STB_GLOBAL)
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
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ef3e0)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff819ef3e0-ffffffff819ef6f9: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ac1a0)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff819ac1a0-ffffffff819ac4b9: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a59e60)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a59e60-ffffffff81a5a179: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 rt6_multipath_hash(const struct net *net, const struct flowi6 *fl6, const struct sk_buff *skb, struct flow_keys *flkeys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a660c0)
Location: net/ipv6/route.c:2329
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_input
  - net/ipv6/route.c:fib6_select_path
  - net/ipv6/icmp.c:icmp6_send
```
**Symbols:**

```
ffffffff81a660c0-ffffffff81a663d9: rt6_multipath_hash (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param reordered. </b>
<code>fl6, skb</code> ➡️ <code>net, fl6, skb, flkeys</code>
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
