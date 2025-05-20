# Function: <code>__skb_warn_lro_forwarding</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705ad0)
Location: net/core/skbuff.c:4176
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81705ad0-ffffffff81705afb: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c7a0)
Location: net/core/skbuff.c:4217
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff8176c7a0-ffffffff8176c7cb: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799970)
Location: net/core/skbuff.c:4261
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81799970-ffffffff8179999b: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b8610)
Location: net/core/skbuff.c:4355
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff817b8610-ffffffff817b863b: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81830fe0)
Location: net/core/skbuff.c:4743
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81830fe0-ffffffff8183100b: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:4782
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff8188345a-ffffffff8188346f: __skb_warn_lro_forwarding.cold.84 (STB_LOCAL)
ffffffff8187b490-ffffffff8187b4ad: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818a3ea1)
Location: net/core/skbuff.c:4804
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff818a3ea1-ffffffff818a3eb6: __skb_warn_lro_forwarding.cold.85 (STB_LOCAL)
ffffffff8189c2d0-ffffffff8189c2ed: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818eecc6)
Location: net/core/skbuff.c:4989
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff818eecc6-ffffffff818eecdb: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff818e6b50-ffffffff818e6b6d: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81920ca2)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81920ca2-ffffffff81920cb7: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff81918ca0-ffffffff81918cbd: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff819f4a2f)
Location: net/core/skbuff.c:5103
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff819f4a2f-ffffffff819f4a44: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff819ea5c0-ffffffff819ea5e0: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81c309a8)
Location: net/core/skbuff.c:5170
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81c309a8-ffffffff81c309bd: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff819ea300-ffffffff819ea320: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81c22c8f)
Location: net/core/skbuff.c:5258
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81c22c8f-ffffffff81c22ca4: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff819d08c0-ffffffff819d08e0: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81d35117)
Location: net/core/skbuff.c:5326
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81d35117-ffffffff81d3512c: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff81a804c0-ffffffff81a804e0: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81f01674)
Location: net/core/skbuff.c:5240
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81f01674-ffffffff81f01689: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff81bf4b50-ffffffff81bf4b7a: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2a00)
Location: net/core/skbuff.c:5442
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81da2a00-ffffffff81da2a46: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e11590)
Location: net/core/skbuff.c:5640
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81e11590-ffffffff81e115d6: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ece0d0)
Location: net/core/skbuff.c:5771
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81ece0d0-ffffffff81ece11d: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb1d88)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffff800010bb1d88-ffff800010bb1dc8: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf6f0)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
c0ccf6f0-c0ccf728: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c89530)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
c000000000c89530-c000000000c89590: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000744466)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffe000744466-ffffffe0007444a4: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff818c0ca2)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff818c0ca2-ffffffff818c0cb7: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff818b8ca0-ffffffff818b8cbd: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff8187abe2)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff8187abe2-ffffffff8187abf7: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff81872bf0-ffffffff81872c0d: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81911ca2)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81911ca2-ffffffff81911cb7: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff81909ca0-ffffffff81909cbd: __skb_warn_lro_forwarding (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __skb_warn_lro_forwarding(const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (ffffffff81932e02)
Location: net/core/skbuff.c:5001
Inline: True
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/seg6_local.c:input_action_end_dx2
```
**Symbols:**

```
ffffffff81932e02-ffffffff81932e17: __skb_warn_lro_forwarding.cold (STB_LOCAL)
ffffffff8192ada0-ffffffff8192adbd: __skb_warn_lro_forwarding (STB_GLOBAL)
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
