# Function: <code>validate_xmit_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff8171c580)
Location: net/core/dev.c:2761
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:__dev_queue_xmit
Direct callers:
  - net/core/dev.c:validate_xmit_skb_list
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff8171c580-ffffffff8171c823: validate_xmit_skb.isra.97.part.98 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81784ef0)
Location: net/core/dev.c:2962
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff81784ef0-ffffffff81785185: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b2500)
Location: net/core/dev.c:2959
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff817b2500-ffffffff817b2795: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cfd00)
Location: net/core/dev.c:3037
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff817cfd00-ffffffff817cff8f: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81849650)
Location: net/core/dev.c:3064
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff81849650-ffffffff818498df: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81893650)
Location: net/core/dev.c:3088
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff81893650-ffffffff8189393c: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b4070)
Location: net/core/dev.c:3332
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff818b4070-ffffffff818b435e: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3334
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff81900940-ffffffff81900c80: validate_xmit_skb (STB_LOCAL)
ffffffff819073f6-ffffffff81907407: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff81932c70-ffffffff81932fb0: validate_xmit_skb (STB_LOCAL)
ffffffff819399f0-ffffffff81939a01: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3610
Inline: False
Direct callers:
  - net/core/dev.c:dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a07c10-ffffffff81a07dd2: validate_xmit_skb (STB_LOCAL)
ffffffff81a0efb8-ffffffff81a0efc9: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3640
Inline: False
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81a092e0-ffffffff81a094b6: validate_xmit_skb (STB_LOCAL)
ffffffff81c312e0-ffffffff81c312f1: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3719
Inline: False
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff819efc60-ffffffff819efe22: validate_xmit_skb (STB_LOCAL)
ffffffff81c235a6-ffffffff81c235b7: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3649
Inline: False
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81aa1080-ffffffff81aa125b: validate_xmit_skb (STB_LOCAL)
ffffffff81d36344-ffffffff81d36375: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3655
Inline: False
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81c18ea0-ffffffff81c1912d: validate_xmit_skb (STB_LOCAL)
ffffffff81f02b1a-ffffffff81f02b4b: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3642
Inline: False
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81dc9e70-ffffffff81dca10c: validate_xmit_skb (STB_LOCAL)
ffffffff820ab600-ffffffff820ab620: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3602
Inline: False
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81e3aa00-ffffffff81e3ac83: validate_xmit_skb (STB_LOCAL)
ffffffff8212cd90-ffffffff8212cda9: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3612
Inline: False
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
```
**Symbols:**

```
ffffffff81ef8db0-ffffffff81ef901e: validate_xmit_skb (STB_LOCAL)
ffffffff8220eaf9-ffffffff8220eb12: validate_xmit_skb.cold (STB_LOCAL)
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
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0c90)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffff800010bd0c90-ffff800010bd0fa0: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceb8c8)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
c0ceb8c8-c0cebc04: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caecf0)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
c000000000caecf0-c000000000caf170: validate_xmit_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b304)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffe00075b304-ffffffe00075b5b2: validate_xmit_skb (STB_LOCAL)
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
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff818d2c70-ffffffff818d2fb0: validate_xmit_skb (STB_LOCAL)
ffffffff818d99c0-ffffffff818d99d1: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff8188cb00-ffffffff8188ce40: validate_xmit_skb (STB_LOCAL)
ffffffff81893800-ffffffff81893811: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff81923c70-ffffffff81923fb0: validate_xmit_skb (STB_LOCAL)
ffffffff8192a9f0-ffffffff8192aa01: validate_xmit_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct sk_buff *validate_xmit_skb(struct sk_buff *skb, struct net_device *dev, bool *again);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:3252
Inline: False
Direct callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:validate_xmit_skb_list
```
**Symbols:**

```
ffffffff819450e0-ffffffff81945420: validate_xmit_skb (STB_LOCAL)
ffffffff8194c0c0-ffffffff8194c0d1: validate_xmit_skb.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *again</code>
</li>
</ul>
</details>
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
