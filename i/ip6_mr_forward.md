# Function: <code>ip6_mr_forward</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr6_table *mrt, struct sk_buff *skb, struct mfc6_cache *cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff817fa1b0)
Location: net/ipv6/ip6mr.c:2083
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6_mr_input
```
**Symbols:**

```
ffffffff817fa1b0-ffffffff817fa464: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr6_table *mrt, struct sk_buff *skb, struct mfc6_cache *cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81869a10)
Location: net/ipv6/ip6mr.c:2086
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81869a10-ffffffff81869cbe: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr6_table *mrt, struct sk_buff *skb, struct mfc6_cache *cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8189c860)
Location: net/ipv6/ip6mr.c:2086
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff8189c860-ffffffff8189cb0e: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr6_table *mrt, struct sk_buff *skb, struct mfc6_cache *cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff818c2c30)
Location: net/ipv6/ip6mr.c:2095
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff818c2c30-ffffffff818c2f51: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr6_table *mrt, struct sk_buff *skb, struct mfc6_cache *cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81945050)
Location: net/ipv6/ip6mr.c:2100
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
```
**Symbols:**

```
ffffffff81945050-ffffffff81945371: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8199e370)
Location: net/ipv6/ip6mr.c:2044
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff8199e370-ffffffff8199e68a: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d4eb0)
Location: net/ipv6/ip6mr.c:2063
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819d4eb0-ffffffff819d51c7: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a43d20)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a43d20-ffffffff81a43fee: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a7a910)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a7a910-ffffffff81a7abde: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b761c0)
Location: net/ipv6/ip6mr.c:2086
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
**Symbols:**

```
ffffffff81b761c0-ffffffff81b7648e: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b84f50)
Location: net/ipv6/ip6mr.c:2087
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_cache_resolve
```
**Symbols:**

```
ffffffff81b84f50-ffffffff81b85246: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b73c00)
Location: net/ipv6/ip6mr.c:2087
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81b73c00-ffffffff81b73ef6: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:2088
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81c3e220-ffffffff81c3e79d: ip6_mr_forward (STB_LOCAL)
ffffffff81d4135d-ffffffff81d41397: ip6_mr_forward.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:2106
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81ddc8b0-ffffffff81ddcf13: ip6_mr_forward (STB_LOCAL)
ffffffff81f0dc9d-ffffffff81f0dcf4: ip6_mr_forward.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:2118
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81fad970-ffffffff81fadfdc: ip6_mr_forward (STB_LOCAL)
ffffffff820b5058-ffffffff820b50a2: ip6_mr_forward.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:2110
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff8200e120-ffffffff8200e790: ip6_mr_forward (STB_LOCAL)
ffffffff82135f30-ffffffff82135f7a: ip6_mr_forward.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:2108
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff820dccb0-ffffffff820dd320: ip6_mr_forward (STB_LOCAL)
ffffffff82217b65-ffffffff82217baf: ip6_mr_forward.cold (STB_LOCAL)
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
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d443e0)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffff800010d443e0-ffff800010d446ec: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e46af4)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c0e46af4-c0e46e30: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e7a910)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
c000000000e7a910-c000000000e7ad28: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe0008802b6)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffe0008802b6-ffffffe00088055c: ip6_mr_forward (STB_LOCAL)
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
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a19fa0)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a19fa0-ffffffff81a1a26e: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d6d60)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff819d6d60-ffffffff819d702e: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a84a20)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a84a20-ffffffff81a84cee: ip6_mr_forward (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip6_mr_forward(struct net *net, struct mr_table *mrt, struct net_device *dev, struct sk_buff *skb, struct mfc6_cache *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a91370)
Location: net/ipv6/ip6mr.c:2081
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
**Symbols:**

```
ffffffff81a91370-ffffffff81a9166e: ip6_mr_forward (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mfc6_cache *c</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mfc6_cache *cache</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct mr6_table *mrt</code> ➡️ <code>struct mr_table *mrt</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, mrt, skb, c</code> ➡️ <code>net, mrt, dev, skb, c</code>
</li>
</ul>
</details>
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
