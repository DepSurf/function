# Function: <code>skb_defer_rx_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2987
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3194
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3320
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3504
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff818c6d90)
Location: net/core/timestamping.c:58
Inline: True
```
**Symbols:**

```
ffffffff818c6d90-ffffffff818c6e41: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff818efee0)
Location: net/core/timestamping.c:58
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff818efee0-ffffffff818eff85: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff819417c0)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list
```
**Symbols:**

```
ffffffff819417c0-ffffffff8194187c: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff819766d0)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff819766d0-ffffffff8197678c: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81a4b430)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff81a4b430-ffffffff81a4b4ec: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81a51050)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff81a51050-ffffffff81a5110c: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81a368d0)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81a368d0-ffffffff81a3698c: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81aec620)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81aec620-ffffffff81aec6dc: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81c6ef60)
Location: net/core/timestamping.c:45
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81c6ef60-ffffffff81c6f037: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81e26cf0)
Location: net/core/timestamping.c:45
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81e26cf0-ffffffff81e26dc7: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81e9c290)
Location: net/core/timestamping.c:45
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81e9c290-ffffffff81e9c367: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81f5ea20)
Location: net/core/timestamping.c:45
Inline: False
Direct callers:
  - net/core/dev.c:netif_receive_skb
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81f5ea20-ffffffff81f5eaf7: skb_defer_rx_timestamp (STB_GLOBAL)
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
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffff800010c1ccc8)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffff800010c1ccc8-ffff800010c1cd8c: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (c0d34b88)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
c0d34b88-c0d34c50: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (c000000000d0dc80)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
c000000000d0dc80-c000000000d0dda8: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffe000796a46)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffe000796a46-ffffffe000796ae0: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3775
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:3775
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff819676d0)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff819676d0-ffffffff8196778c: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool skb_defer_rx_timestamp(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/timestamping.c (ffffffff81989960)
Location: net/core/timestamping.c:45
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_list_internal
```
**Symbols:**

```
ffffffff81989960-ffffffff81989a1c: skb_defer_rx_timestamp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
