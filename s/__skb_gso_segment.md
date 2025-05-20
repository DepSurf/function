# Function: <code>__skb_gso_segment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171c260)
Location: net/core/dev.c:2548
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff8171c260-ffffffff8171c321: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81784b00)
Location: net/core/dev.c:2705
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff81784b00-ffffffff81784c42: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b2130)
Location: net/core/dev.c:2702
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/ipv4/ip_output.c:ip_finish_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff817b2130-ffffffff817b2272: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cf910)
Location: net/core/dev.c:2760
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/ipv4/ip_output.c:ip_finish_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff817cf910-ffffffff817cfa9b: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81849250)
Location: net/core/dev.c:2787
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/ipv4/ip_output.c:ip_finish_output
  - net/xfrm/xfrm_output.c:xfrm_output
```
**Symbols:**

```
ffffffff81849250-ffffffff818493e7: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81893220)
Location: net/core/dev.c:2829
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/ipv4/ip_output.c:ip_finish_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81893220-ffffffff818933a3: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b3c60)
Location: net/core/dev.c:3066
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/ipv4/ip_output.c:ip_finish_output
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff818b3c60-ffffffff818b3ddd: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819004e0)
Location: net/core/dev.c:3074
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff819004e0-ffffffff81900673: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81932810)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81932810-ffffffff819329a3: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a077f0)
Location: net/core/dev.c:3350
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/ipv4/ip_output.c:ip_finish_output_gso
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81a077f0-ffffffff81a07967: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a08e80)
Location: net/core/dev.c:3375
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/ipv4/ip_output.c:ip_finish_output_gso
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81a08e80-ffffffff81a08ff7: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ef810)
Location: net/core/dev.c:3443
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff819ef810-ffffffff819ef987: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa0c30)
Location: net/core/dev.c:3370
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81aa0c30-ffffffff81aa0da7: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c12060)
Location: net/core/dev.c:3377
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81c12060-ffffffff81c121d1: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc2430)
Location: net/core/dev.c:3364
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81dc2430-ffffffff81dc25a1: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81e7d6b0)
Location: net/core/gso.c:88
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81e7d6b0-ffffffff81e7d821: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81f3e630)
Location: net/core/gso.c:88
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81f3e630-ffffffff81f3e79e: __skb_gso_segment (STB_GLOBAL)
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
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd08a0)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffff800010bd08a0-ffff800010bd0a00: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceb3d4)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
c0ceb3d4-c0ceb590: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cae790)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
c000000000cae790-c000000000cae9a8: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075afbc)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffe00075afbc-ffffffe00075b0ea: __skb_gso_segment (STB_GLOBAL)
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
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d2810)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff818d2810-ffffffff818d29a3: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c6a0)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff8188c6a0-ffffffff8188c833: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81923810)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81923810-ffffffff819239a3: __skb_gso_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *__skb_gso_segment(struct sk_buff *skb, netdev_features_t features, bool tx_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81944c80)
Location: net/core/dev.c:2992
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
**Symbols:**

```
ffffffff81944c80-ffffffff81944e13: __skb_gso_segment (STB_GLOBAL)
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
