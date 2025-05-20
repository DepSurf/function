# Function: <code>udp6_lib_lookup2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, struct udp_hslot *hslot2, unsigned int slot2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff817e3690)
Location: net/ipv6/udp.c:235
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff817e3690-ffffffff817e398e: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81851a40)
Location: net/ipv6/udp.c:165
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81851a40-ffffffff81851bbe: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81883800)
Location: net/ipv6/udp.c:165
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81883800-ffffffff8188397e: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, bool exact_dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff818a9a90)
Location: net/ipv6/udp.c:176
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff818a9a90-ffffffff818a9be7: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, bool exact_dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff8192c480)
Location: net/ipv6/udp.c:180
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff8192c480-ffffffff8192c5e1: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, bool exact_dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819848e0)
Location: net/ipv6/udp.c:164
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff819848e0-ffffffff819849c9: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, bool exact_dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bac80)
Location: net/ipv6/udp.c:158
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff819bac80-ffffffff819bafa9: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a28b50)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81a28b50-ffffffff81a28ecd: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a5f690)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81a5f690-ffffffff81a5fa14: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b59490)
Location: net/ipv6/udp.c:145
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81b59490-ffffffff81b59667: udp6_lib_lookup2.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b67ac0)
Location: net/ipv6/udp.c:163
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81b67ac0-ffffffff81b67cc2: udp6_lib_lookup2.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/udp.c (ffffffff81b55ca0)
Location: net/ipv6/udp.c:163
Inline: True
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81b55ca0-ffffffff81b55ea3: udp6_lib_lookup2.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81c1b760)
Location: net/ipv6/udp.c:165
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81c1b760-ffffffff81c1b95f: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81db7ea0)
Location: net/ipv6/udp.c:167
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81db7ea0-ffffffff81db80c1: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81f87ee0)
Location: net/ipv6/udp.c:181
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81f87ee0-ffffffff81f880e3: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81fea990)
Location: net/ipv6/udp.c:183
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81fea990-ffffffff81feab11: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff820b5820)
Location: net/ipv6/udp.c:166
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff820b5820-ffffffff820b5994: udp6_lib_lookup2 (STB_LOCAL)
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
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffff800010d23b18)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffff800010d23b18-ffff800010d23ec4: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c0e29570)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
c0e29570-c0e29950: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (c000000000e55a40)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
c000000000e55a40-c000000000e55ee8: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffe000866754)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffe000866754-ffffffe000866ae6: udp6_lib_lookup2 (STB_LOCAL)
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
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819fed20)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff819fed20-ffffffff819ff0a4: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff819bbae0)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff819bbae0-ffffffff819bbe64: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a697a0)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81a697a0-ffffffff81a69b24: udp6_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *udp6_lib_lookup2(struct net *net, const struct in6_addr *saddr, __be16 sport, const struct in6_addr *daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp.c (ffffffff81a75d80)
Location: net/ipv6/udp.c:145
Inline: False
Direct callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
**Symbols:**

```
ffffffff81a75d80-ffffffff81a76136: udp6_lib_lookup2 (STB_LOCAL)
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
<code>struct sk_buff *skb</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int slot2</code>
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
<b>Param added. </b>
<code>bool exact_dif</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, saddr, sport, daddr, hnum, dif, hslot2, skb</code> ➡️ <code>net, saddr, sport, daddr, hnum, dif, exact_dif, hslot2, skb</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sdif</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, saddr, sport, daddr, hnum, dif, exact_dif, hslot2, skb</code> ➡️ <code>net, saddr, sport, daddr, hnum, dif, sdif, exact_dif, hslot2, skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool exact_dif</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, saddr, sport, daddr, hnum, dif, sdif, exact_dif, hslot2, skb</code> ➡️ <code>net, saddr, sport, daddr, hnum, dif, sdif, hslot2, skb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
