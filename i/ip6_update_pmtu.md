# Function: <code>ip6_update_pmtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d6e80)
Location: net/ipv6/route.c:1388
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff817d6e80-ffffffff817d6f73: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81845510)
Location: net/ipv6/route.c:1399
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81845510-ffffffff81845601: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818772b0)
Location: net/ipv6/route.c:1410
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff818772b0-ffffffff8187739b: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189c590)
Location: net/ipv6/route.c:1447
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff8189c590-ffffffff8189c69b: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191c600)
Location: net/ipv6/route.c:2120
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff8191c600-ffffffff8191c6f8: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81974b70)
Location: net/ipv6/route.c:2364
Inline: False
Direct callers:
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81974b70-ffffffff81974c69: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aa790)
Location: net/ipv6/route.c:2355
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff819aa790-ffffffff819aa889: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a17bf0)
Location: net/ipv6/route.c:2773
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81a17bf0-ffffffff81a17cd7: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4e830)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81a4e830-ffffffff81a4e92f: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b46170)
Location: net/ipv6/route.c:2807
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81b46170-ffffffff81b4625d: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b54ca0)
Location: net/ipv6/route.c:2791
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81b54ca0-ffffffff81b54d8d: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b42730)
Location: net/ipv6/route.c:2800
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81b42730-ffffffff81b4281c: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c07e80)
Location: net/ipv6/route.c:2930
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81c07e80-ffffffff81c07f6c: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da2b50)
Location: net/ipv6/route.c:2926
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81da2b50-ffffffff81da2c71: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f71f30)
Location: net/ipv6/route.c:2926
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81f71f30-ffffffff81f72051: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd2020)
Location: net/ipv6/route.c:2925
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81fd2020-ffffffff81fd2141: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209f5b0)
Location: net/ipv6/route.c:2927
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff8209f5b0-ffffffff8209f6d1: ip6_update_pmtu (STB_GLOBAL)
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
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d12658)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffff800010d12658-ffff800010d12774: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e18338)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
c0e18338-c0e18444: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3eaf0)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
c000000000e3eaf0-c000000000e3ec70: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085898a)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffe00085898a-ffffffe000858ab8: ip6_update_pmtu (STB_GLOBAL)
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
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819edec0)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff819edec0-ffffffff819edfbf: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aac80)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff819aac80-ffffffff819aad7f: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a58940)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81a58940-ffffffff81a58a3f: ip6_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_update_pmtu(struct sk_buff *skb, struct net *net, __be32 mtu, int oif, u32 mark, kuid_t uid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a64b00)
Location: net/ipv6/route.c:2783
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_sk_update_pmtu
  - net/ipv6/icmp.c:icmpv6_err
```
**Symbols:**

```
ffffffff81a64b00-ffffffff81a64bff: ip6_update_pmtu (STB_GLOBAL)
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
