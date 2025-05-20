# Function: <code>ip6mr_get_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, int nowait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff817fb930)
Location: net/ipv6/ip6mr.c:2278
Inline: False
```
**Symbols:**

```
ffffffff817fb930-ffffffff817fbc48: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, int nowait, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8186b1e0)
Location: net/ipv6/ip6mr.c:2288
Inline: False
```
**Symbols:**

```
ffffffff8186b1e0-ffffffff8186b51d: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, int nowait, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8189e040)
Location: net/ipv6/ip6mr.c:2288
Inline: False
```
**Symbols:**

```
ffffffff8189e040-ffffffff8189e37d: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff818c4640)
Location: net/ipv6/ip6mr.c:2299
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff818c4640-ffffffff818c48ef: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819478e0)
Location: net/ipv6/ip6mr.c:2304
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819478e0-ffffffff81947b8f: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819a0930)
Location: net/ipv6/ip6mr.c:2200
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819a0930-ffffffff819a0c0e: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d7530)
Location: net/ipv6/ip6mr.c:2232
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819d7530-ffffffff819d7821: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a465d0)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a465d0-ffffffff81a46894: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a7d1c0)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a7d1c0-ffffffff81a7d484: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b77b70)
Location: net/ipv6/ip6mr.c:2255
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81b77b70-ffffffff81b77e2e: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b86af0)
Location: net/ipv6/ip6mr.c:2256
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81b86af0-ffffffff81b86dae: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b757b0)
Location: net/ipv6/ip6mr.c:2256
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81b757b0-ffffffff81b75a79: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81c401c0)
Location: net/ipv6/ip6mr.c:2257
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81c401c0-ffffffff81c404ee: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81dde7d0)
Location: net/ipv6/ip6mr.c:2278
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81dde7d0-ffffffff81ddeb2c: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81fb0a00)
Location: net/ipv6/ip6mr.c:2283
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81fb0a00-ffffffff81fb0ce3: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff820110b0)
Location: net/ipv6/ip6mr.c:2275
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff820110b0-ffffffff8201139c: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff820e0040)
Location: net/ipv6/ip6mr.c:2273
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff820e0040-ffffffff820e032c: ip6mr_get_route (STB_GLOBAL)
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
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d47e68)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffff800010d47e68-ffff800010d4815c: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e498f0)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c0e498f0-c0e49b6c: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e7d2f0)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c000000000e7d2f0-c000000000e7d694: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe000881a4a)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffe000881a4a-ffffffe000881c66: ip6mr_get_route (STB_GLOBAL)
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
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a1c850)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a1c850-ffffffff81a1cb14: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d9610)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819d9610-ffffffff819d98d4: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a872d0)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a872d0-ffffffff81a87594: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6mr_get_route(struct net *net, struct sk_buff *skb, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a93ea0)
Location: net/ipv6/ip6mr.c:2250
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a93ea0-ffffffff81a9416c: ip6mr_get_route (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 portid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nowait</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, skb, rtm, nowait, portid</code> ➡️ <code>net, skb, rtm, portid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
