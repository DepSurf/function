# Function: <code>__kfree_skb_defer</code>

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
In net/core/skbuff.c (ffffffff8170699f)
Location: net/core/skbuff.c:772
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81773ae0)
Location: net/core/skbuff.c:795
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff81773ae0-ffffffff81773b46: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817a0d10)
Location: net/core/skbuff.c:795
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff817a0d10-ffffffff817a0d71: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bdd10)
Location: net/core/skbuff.c:801
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff817bdd10-ffffffff817bdd71: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81837360)
Location: net/core/skbuff.c:753
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff81837360-ffffffff818373c1: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81881820)
Location: net/core/skbuff.c:753
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff81881820-ffffffff8188187e: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a2340)
Location: net/core/skbuff.c:757
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff818a2340-ffffffff818a239e: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ed010)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff818ed010-ffffffff818ed071: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191f130)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff8191f130-ffffffff8191f191: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f2280)
Location: net/core/skbuff.c:889
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff819f2280-ffffffff819f22f8: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f2280)
Location: net/core/skbuff.c:901
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff819f2280-ffffffff819f22f8: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d83d0)
Location: net/core/skbuff.c:934
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff819d83d0-ffffffff819d8448: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a88220)
Location: net/core/skbuff.c:950
Inline: False
Direct callers:
  - net/core/dev.c:napi_gro_receive
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff81a88220-ffffffff81a88298: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfd860)
Location: net/core/skbuff.c:955
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81bfd860-ffffffff81bfd8f0: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dae570)
Location: net/core/skbuff.c:1136
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
  - net/core/gro.c:napi_gro_receive
```
**Symbols:**

```
ffffffff81dae570-ffffffff81dae605: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb9af0)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffff800010bb9af0-ffff800010bb9b70: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd6404)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
c0cd6404-c0cd6470: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c92120)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
c000000000c92120-c000000000c921d8: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000748fb8)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffe000748fb8-ffffffe00074904a: __kfree_skb_defer (STB_GLOBAL)
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
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bf130)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff818bf130-ffffffff818bf191: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81879070)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff81879070-ffffffff818790d1: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81910130)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff81910130-ffffffff81910191: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __kfree_skb_defer(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81931290)
Location: net/core/skbuff.c:890
Inline: False
Direct callers:
  - net/core/dev.c:net_tx_action
```
**Symbols:**

```
ffffffff81931290-ffffffff819312f1: __kfree_skb_defer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
