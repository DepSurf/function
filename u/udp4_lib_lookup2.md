# Function: <code>udp4_lib_lookup2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, struct udp_hslot *hslot2, unsigned int slot2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81788d60)
Location: net/ipv4/udp.c:441
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81788d60-ffffffff81789000: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f66b0)
Location: net/ipv4/udp.c:450
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff817f66b0-ffffffff817f6806: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81827610)
Location: net/ipv4/udp.c:451
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81827610-ffffffff81827766: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, bool exact_dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81848d90)
Location: net/ipv4/udp.c:438
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81848d90-ffffffff81848edb: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, bool exact_dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c87e0)
Location: net/ipv4/udp.c:440
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff818c87e0-ffffffff818c8935: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, bool exact_dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191cd80)
Location: net/ipv4/udp.c:428
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff8191cd80-ffffffff8191ce61: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, bool exact_dif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8194bc70)
Location: net/ipv4/udp.c:425
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff8194bc70-ffffffff8194bee2: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819b0400)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff819b0400-ffffffff819b06b9: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e70c0)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff819e70c0-ffffffff819e7383: udp4_lib_lookup2 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81ad2980)
Location: net/ipv4/udp.c:412
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81ad2980-ffffffff81ad2c4a: udp4_lib_lookup2.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81adeee0)
Location: net/ipv4/udp.c:429
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81adeee0-ffffffff81adf0b9: udp4_lib_lookup2.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81ac9f30)
Location: net/ipv4/udp.c:429
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81ac9f30-ffffffff81aca10a: udp4_lib_lookup2.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b887b0)
Location: net/ipv4/udp.c:430
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81b887b0-ffffffff81b88989: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d19c60)
Location: net/ipv4/udp.c:430
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81d19c60-ffffffff81d19e4c: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee0840)
Location: net/ipv4/udp.c:437
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81ee0840-ffffffff81ee0a16: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3fb20)
Location: net/ipv4/udp.c:439
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81f3fb20-ffffffff81f3fc99: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82004300)
Location: net/ipv4/udp.c:423
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff82004300-ffffffff8200445e: udp4_lib_lookup2 (STB_LOCAL)
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
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c99a00)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffff800010c99a00-ffff800010c99cc4: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0daacf0)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
c0daacf0-c0daafbc: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dae4f0)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
c000000000dae4f0-c000000000dae8a4: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f961a)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffe0007f961a-ffffffe0007f9852: udp4_lib_lookup2 (STB_LOCAL)
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
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81986f30)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff81986f30-ffffffff819871f3: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819409f0)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff819409f0-ffffffff81940cb3: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f1700)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff819f1700-ffffffff819f19c3: udp4_lib_lookup2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *udp4_lib_lookup2(struct net *net, __be32 saddr, __be16 sport, __be32 daddr, unsigned int hnum, int dif, int sdif, struct udp_hslot *hslot2, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819fca00)
Location: net/ipv4/udp.c:409
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
**Symbols:**

```
ffffffff819fca00-ffffffff819fccc8: udp4_lib_lookup2 (STB_LOCAL)
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
