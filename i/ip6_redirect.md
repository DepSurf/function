# Function: <code>ip6_redirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d7b40)
Location: net/ipv6/route.c:1493
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff817d7b40-ffffffff817d7c0b: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818463a0)
Location: net/ipv6/route.c:1517
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff818463a0-ffffffff8184646b: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81878100)
Location: net/ipv6/route.c:1529
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81878100-ffffffff818781d0: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189d2f0)
Location: net/ipv6/route.c:1566
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff8189d2f0-ffffffff8189d3cb: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191cc60)
Location: net/ipv6/route.c:2254
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff8191cc60-ffffffff8191cd3b: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819753a0)
Location: net/ipv6/route.c:2523
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff819753a0-ffffffff8197548c: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aafe0)
Location: net/ipv6/route.c:2516
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff819aafe0-ffffffff819ab0cc: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a18300)
Location: net/ipv6/route.c:2988
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81a18300-ffffffff81a183e3: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4ef60)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81a4ef60-ffffffff81a4f043: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b468a0)
Location: net/ipv6/route.c:3022
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81b468a0-ffffffff81b46983: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b553e0)
Location: net/ipv6/route.c:3006
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81b553e0-ffffffff81b554c3: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b42e50)
Location: net/ipv6/route.c:3015
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81b42e50-ffffffff81b42f33: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c085a0)
Location: net/ipv6/route.c:3145
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81c085a0-ffffffff81c08683: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da33a0)
Location: net/ipv6/route.c:3135
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81da33a0-ffffffff81da3493: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f727c0)
Location: net/ipv6/route.c:3135
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81f727c0-ffffffff81f728b3: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd28b0)
Location: net/ipv6/route.c:3135
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81fd28b0-ffffffff81fd29a3: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209fe40)
Location: net/ipv6/route.c:3137
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff8209fe40-ffffffff8209ff33: ip6_redirect (STB_GLOBAL)
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
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d12bf8)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffff800010d12bf8-ffff800010d12ce4: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e18a08)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
c0e18a08-c0e18af8: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3f490)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
c000000000e3f490-c000000000e3f5c0: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000859016)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffe000859016-ffffffe0008590f6: ip6_redirect (STB_GLOBAL)
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
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ee5f0)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff819ee5f0-ffffffff819ee6d3: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ab3b0)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff819ab3b0-ffffffff819ab493: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a59070)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81a59070-ffffffff81a59153: ip6_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_redirect(struct sk_buff *skb, struct net *net, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a65270)
Location: net/ipv6/route.c:2998
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_redirect
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81a65270-ffffffff81a65353: ip6_redirect (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>kuid_t uid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
