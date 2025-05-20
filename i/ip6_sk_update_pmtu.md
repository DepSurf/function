# Function: <code>ip6_sk_update_pmtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff817d6f80)
Location: net/ipv6/route.c:1409
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff817d6f80-ffffffff817d6fa1: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81845610)
Location: net/ipv6/route.c:1420
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81845610-ffffffff818456b5: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff818773a0)
Location: net/ipv6/route.c:1432
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff818773a0-ffffffff8187744c: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189c6a0)
Location: net/ipv6/route.c:1469
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff8189c6a0-ffffffff8189c74c: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191c700)
Location: net/ipv6/route.c:2142
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff8191c700-ffffffff8191c7ae: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81974c70)
Location: net/ipv6/route.c:2386
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81974c70-ffffffff81974d23: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aa890)
Location: net/ipv6/route.c:2376
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff819aa890-ffffffff819aa96f: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a17ce0)
Location: net/ipv6/route.c:2794
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81a17ce0-ffffffff81a17dcf: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4e930)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81a4e930-ffffffff81a4ea1f: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b46260)
Location: net/ipv6/route.c:2828
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81b46260-ffffffff81b4634f: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b54d90)
Location: net/ipv6/route.c:2812
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81b54d90-ffffffff81b54e90: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b42820)
Location: net/ipv6/route.c:2821
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81b42820-ffffffff81b42920: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2951
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81d3fdb8-ffffffff81d3fdd8: ip6_sk_update_pmtu.cold (STB_LOCAL)
ffffffff81c07f70-ffffffff81c0807d: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2947
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81f0c856-ffffffff81f0c876: ip6_sk_update_pmtu.cold (STB_LOCAL)
ffffffff81da2c80-ffffffff81da2db4: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2947
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff820b3ea7-ffffffff820b3ec7: ip6_sk_update_pmtu.cold (STB_LOCAL)
ffffffff81f72070-ffffffff81f721a4: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2946
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff82134f75-ffffffff82134f8e: ip6_sk_update_pmtu.cold (STB_LOCAL)
ffffffff81fd2160-ffffffff81fd2296: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2948
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff82216959-ffffffff82216972: ip6_sk_update_pmtu.cold (STB_LOCAL)
ffffffff8209f6f0-ffffffff8209f826: ip6_sk_update_pmtu (STB_GLOBAL)
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
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d13310)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffff800010d13310-ffff800010d1344c: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e18444)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
c0e18444-c0e18550: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3ec70)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
c000000000e3ec70-c000000000e3ee00: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000858ab8)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffe000858ab8-ffffffe000858bc0: ip6_sk_update_pmtu (STB_GLOBAL)
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
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819edfc0)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff819edfc0-ffffffff819ee0af: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aad80)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff819aad80-ffffffff819aae6f: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a58a40)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81a58a40-ffffffff81a58b2f: ip6_sk_update_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_sk_update_pmtu(struct sk_buff *skb, struct sock *sk, __be32 mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a64c00)
Location: net/ipv6/route.c:2804
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_err
  - net/ipv6/raw.c:raw6_icmp_error
```
**Symbols:**

```
ffffffff81a64c00-ffffffff81a64d0c: ip6_sk_update_pmtu (STB_GLOBAL)
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
