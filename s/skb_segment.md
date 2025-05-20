# Function: <code>skb_segment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8170aa80)
Location: net/core/skbuff.c:3052
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff8170aa80-ffffffff8170b533: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81772680)
Location: net/core/skbuff.c:3050
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81772680-ffffffff8177326c: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179f770)
Location: net/core/skbuff.c:3047
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff8179f770-ffffffff817a0472: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817be7d0)
Location: net/core/skbuff.c:3088
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff817be7d0-ffffffff817bf42b: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818380d0)
Location: net/core/skbuff.c:3470
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
```
**Symbols:**

```
ffffffff818380d0-ffffffff81838da3: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3499
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff818834b7-ffffffff818834ed: skb_segment.cold.88 (STB_LOCAL)
ffffffff81882620-ffffffff818833c9: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3478
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff818a3f08-ffffffff818a3f3e: skb_segment.cold.89 (STB_LOCAL)
ffffffff818a30d0-ffffffff818a3e13: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3644
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff818ef20c-ffffffff818ef22f: skb_segment.cold (STB_LOCAL)
ffffffff818edd70-ffffffff818eeb00: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff819211b1-ffffffff819211d4: skb_segment.cold (STB_LOCAL)
ffffffff8191fe60-ffffffff81920c00: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3740
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff819f4adb-ffffffff819f4afe: skb_segment.cold (STB_LOCAL)
ffffffff819f3450-ffffffff819f4286: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3808
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81c30a6f-ffffffff81c30a92: skb_segment.cold (STB_LOCAL)
ffffffff819f3480-ffffffff819f42b0: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3893
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81c22d59-ffffffff81c22d79: skb_segment.cold (STB_LOCAL)
ffffffff819d96e0-ffffffff819da465: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3956
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81d353e0-ffffffff81d3542b: skb_segment.cold (STB_LOCAL)
ffffffff81a896a0-ffffffff81a8a475: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3982
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81f01902-ffffffff81f01947: skb_segment.cold (STB_LOCAL)
ffffffff81bfe9f0-ffffffff81bff8cc: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dad430)
Location: net/core/skbuff.c:4183
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81dad430-ffffffff81dae33b: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1d330)
Location: net/core/skbuff.c:4357
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81e1d330-ffffffff81e1e254: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edaa20)
Location: net/core/skbuff.c:4479
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:udp4_ufo_fragment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv6/udp_offload.c:udp6_ufo_fragment
```
**Symbols:**

```
ffffffff81edaa20-ffffffff81edb95d: skb_segment (STB_GLOBAL)
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
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bba910)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffff800010bba910-ffff800010bbb55c: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd7098)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
c0cd7098-c0cd7d04: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c935a0)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
c000000000c935a0-c000000000c943f8: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000749b16)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffe000749b16-ffffffe00074a5ac: skb_segment (STB_GLOBAL)
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
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff818c11b1-ffffffff818c11d4: skb_segment.cold (STB_LOCAL)
ffffffff818bfe60-ffffffff818c0c00: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff8187b0f1-ffffffff8187b114: skb_segment.cold (STB_LOCAL)
ffffffff81879da0-ffffffff8187ab40: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff819121b1-ffffffff819121d4: skb_segment.cold (STB_LOCAL)
ffffffff81910e60-ffffffff81911c00: skb_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment(struct sk_buff *head_skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3650
Inline: False
Direct callers:
  - net/ipv4/tcp_offload.c:tcp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff8193334e-ffffffff81933371: skb_segment.cold (STB_LOCAL)
ffffffff81931fc0-ffffffff81932d60: skb_segment (STB_GLOBAL)
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
