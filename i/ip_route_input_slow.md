# Function: <code>ip_route_input_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81755469)
Location: net/ipv4/route.c:1769
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c15f8)
Location: net/ipv4/route.c:1776
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f1afc)
Location: net/ipv4/route.c:1792
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818116c1)
Location: net/ipv4/route.c:1873
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81890c79)
Location: net/ipv4/route.c:1888
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1912
Inline: False
```
**Symbols:**

```
ffffffff818e4a40-ffffffff818e5582: ip_route_input_slow (STB_LOCAL)
ffffffff818e771b-ffffffff818e775a: ip_route_input_slow.cold.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1909
Inline: False
```
**Symbols:**

```
ffffffff81911930-ffffffff819124c7: ip_route_input_slow (STB_LOCAL)
ffffffff819145cb-ffffffff8191460a: ip_route_input_slow.cold.67 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2034
Inline: False
```
**Symbols:**

```
ffffffff819740a0-ffffffff81974c0c: ip_route_input_slow (STB_LOCAL)
ffffffff81976ab4-ffffffff81976b0e: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
ffffffff819aaac0-ffffffff819ab62f: ip_route_input_slow (STB_LOCAL)
ffffffff819ad45d-ffffffff819ad49c: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2079
Inline: False
```
**Symbols:**

```
ffffffff81a94df0-ffffffff81a9572a: ip_route_input_slow (STB_LOCAL)
ffffffff81a97215-ffffffff81a9723d: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2085
Inline: False
```
**Symbols:**

```
ffffffff81a9edf0-ffffffff81a9f7ba: ip_route_input_slow (STB_LOCAL)
ffffffff81c324ed-ffffffff81c32515: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2086
Inline: False
```
**Symbols:**

```
ffffffff81a89d50-ffffffff81a8a6f7: ip_route_input_slow (STB_LOCAL)
ffffffff81c247d7-ffffffff81c247ff: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2205
Inline: False
```
**Symbols:**

```
ffffffff81b44be0-ffffffff81b455ba: ip_route_input_slow (STB_LOCAL)
ffffffff81d39eef-ffffffff81d39fb4: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2227
Inline: False
```
**Symbols:**

```
ffffffff81cd18e0-ffffffff81cd22d7: ip_route_input_slow (STB_LOCAL)
ffffffff81f06645-ffffffff81f0670b: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2222
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81e91e20-ffffffff81e9281e: ip_route_input_slow (STB_LOCAL)
ffffffff820ae18e-ffffffff820ae232: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2220
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81ef05a0-ffffffff81ef0fb3: ip_route_input_slow (STB_LOCAL)
ffffffff8212f68c-ffffffff8212f730: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2223
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81fb46f0-ffffffff81fb510a: ip_route_input_slow (STB_LOCAL)
ffffffff82211449-ffffffff822114ed: ip_route_input_slow.cold (STB_LOCAL)
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
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5ae58)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
ffff800010c5ae58-ffff800010c5b7a4: ip_route_input_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6a334)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
c0d6a334-c0d6adb8: ip_route_input_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5cb90)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
c000000000d5cb90-c000000000d5d7dc: ip_route_input_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c422e)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
ffffffe0007c422e-ffffffe0007c4a64: ip_route_input_slow (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
ffffffff8194a930-ffffffff8194b49f: ip_route_input_slow (STB_LOCAL)
ffffffff8194d2cd-ffffffff8194d30c: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
ffffffff81904420-ffffffff81904f8f: ip_route_input_slow (STB_LOCAL)
ffffffff81906dbd-ffffffff81906dfc: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
ffffffff819b5100-ffffffff819b5c6f: ip_route_input_slow (STB_LOCAL)
ffffffff819b7a9d-ffffffff819b7adc: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ip_route_input_slow(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2038
Inline: False
```
**Symbols:**

```
ffffffff819be840-ffffffff819bf42f: ip_route_input_slow (STB_LOCAL)
ffffffff819c130d-ffffffff819c134c: ip_route_input_slow.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
