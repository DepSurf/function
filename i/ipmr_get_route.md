# Function: <code>ipmr_get_route</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, int nowait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817aab20)
Location: net/ipv4/ipmr.c:2191
Inline: False
```
**Symbols:**

```
ffffffff817aab20-ffffffff817aad97: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, int nowait, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81818600)
Location: net/ipv4/ipmr.c:2124
Inline: False
```
**Symbols:**

```
ffffffff81818600-ffffffff8181889c: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, int nowait, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81849e60)
Location: net/ipv4/ipmr.c:2135
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81849e60-ffffffff8184a0fc: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186d7f0)
Location: net/ipv4/ipmr.c:2193
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff8186d7f0-ffffffff8186db3b: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818ee120)
Location: net/ipv4/ipmr.c:2358
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff818ee120-ffffffff818ee47b: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81943dd0)
Location: net/ipv4/ipmr.c:2232
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81943dd0-ffffffff8194406d: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81973f20)
Location: net/ipv4/ipmr.c:2245
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
**Symbols:**

```
ffffffff81973f20-ffffffff819741bd: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819dda10)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff819dda10-ffffffff819ddc6c: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a14b30)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81a14b30-ffffffff81a14da9: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b05ab0)
Location: net/ipv4/ipmr.c:2225
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81b05ab0-ffffffff81b05d2b: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b13cd0)
Location: net/ipv4/ipmr.c:2232
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81b13cd0-ffffffff81b13f5a: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b01b10)
Location: net/ipv4/ipmr.c:2232
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81b01b10-ffffffff81b01da0: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bc38f0)
Location: net/ipv4/ipmr.c:2234
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81bc38f0-ffffffff81bc3bdd: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81d58870)
Location: net/ipv4/ipmr.c:2228
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81d58870-ffffffff81d58b94: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f22ce0)
Location: net/ipv4/ipmr.c:2241
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81f22ce0-ffffffff81f22f79: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81f82820)
Location: net/ipv4/ipmr.c:2256
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81f82820-ffffffff81f82ab9: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff82048ea0)
Location: net/ipv4/ipmr.c:2254
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff82048ea0-ffffffff82049139: ipmr_get_route (STB_GLOBAL)
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
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010ccfe30)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffff800010ccfe30-ffff800010cd0190: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dda41c)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
c0dda41c-c0dda700: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000dee070)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
c000000000dee070-c000000000dee3fc: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe000821e9a)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffe000821e9a-ffffffe0008220a6: ipmr_get_route (STB_GLOBAL)
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
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819b41e0)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff819b41e0-ffffffff819b443c: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81970810)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81970810-ffffffff81970a6c: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a1ea80)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81a1ea80-ffffffff81a1ecdc: ipmr_get_route (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipmr_get_route(struct net *net, struct sk_buff *skb, __be32 saddr, __be32 daddr, struct rtmsg *rtm, u32 portid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a29f00)
Location: net/ipv4/ipmr.c:2257
Inline: False
Direct callers:
  - net/ipv4/route.c:rt_fill_info
```
**Symbols:**

```
ffffffff81a29f00-ffffffff81a2a19e: ipmr_get_route (STB_GLOBAL)
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
<code>net, skb, saddr, daddr, rtm, nowait, portid</code> ➡️ <code>net, skb, saddr, daddr, rtm, portid</code>
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
