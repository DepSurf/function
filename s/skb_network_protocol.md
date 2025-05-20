# Function: <code>skb_network_protocol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171c010)
Location: net/core/dev.c:2473
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:skb_mac_gso_segment
  - net/core/dev.c:netif_skb_features
```
**Symbols:**

```
ffffffff8171c010-ffffffff8171c136: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817848b0)
Location: net/core/dev.c:2630
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff817848b0-ffffffff817849d6: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b1ef0)
Location: net/core/dev.c:2627
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff817b1ef0-ffffffff817b200d: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cf6d0)
Location: net/core/dev.c:2684
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff817cf6d0-ffffffff817cf7e3: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81849010)
Location: net/core/dev.c:2711
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81849010-ffffffff81849119: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81892fe0)
Location: net/core/dev.c:2753
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81892fe0-ffffffff818930e2: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b3a50)
Location: net/core/dev.c:2990
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff818b3a50-ffffffff818b3b43: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2998
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff819073e1-ffffffff819073f6: skb_network_protocol.cold (STB_LOCAL)
ffffffff819002e0-ffffffff819003d9: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81932600)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81932600-ffffffff81932703: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a075a0)
Location: net/core/dev.c:3274
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:harmonize_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81a075a0-ffffffff81a076f0: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a08c20)
Location: net/core/dev.c:3299
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:harmonize_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81a08c20-ffffffff81a08d70: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ef5c0)
Location: net/core/dev.c:3367
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff819ef5c0-ffffffff819ef702: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa09e0)
Location: net/core/dev.c:3294
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81aa09e0-ffffffff81aa0b22: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c18a50)
Location: net/core/dev.c:3335
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/gro.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81c18a50-ffffffff81c18ba8: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc9a10)
Location: net/core/dev.c:3322
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/gro.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81dc9a10-ffffffff81dc9b68: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3a530)
Location: net/core/dev.c:3350
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/gso.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81e3a530-ffffffff81e3a6d7: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef88c0)
Location: net/core/dev.c:3357
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/gso.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81ef88c0-ffffffff81ef8a67: skb_network_protocol (STB_GLOBAL)
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
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0640)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffff800010bd0640-ffff800010bd0774: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceb178)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
c0ceb178-c0ceb2ac: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cae420)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
c000000000cae420-c000000000cae62c: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075ade2)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffe00075ade2-ffffffe00075aef4: skb_network_protocol (STB_GLOBAL)
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
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d2600)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff818d2600-ffffffff818d2703: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c490)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff8188c490-ffffffff8188c593: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81923600)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81923600-ffffffff81923703: skb_network_protocol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__be16 skb_network_protocol(struct sk_buff *skb, int *depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81944a50)
Location: net/core/dev.c:2916
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/dev.c:netif_skb_features
  - net/core/dev.c:skb_mac_gso_segment
```
**Symbols:**

```
ffffffff81944a50-ffffffff81944b53: skb_network_protocol (STB_GLOBAL)
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
