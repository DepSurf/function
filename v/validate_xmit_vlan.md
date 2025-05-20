# Function: <code>validate_xmit_vlan</code>

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
In net/core/dev.c (ffffffff8171c5a1)
Location: net/core/dev.c:2752
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
In net/core/dev.c (ffffffff81784f11)
Location: net/core/dev.c:2953
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff817b2521)
Location: net/core/dev.c:2950
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff817cfd24)
Location: net/core/dev.c:3017
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff81849674)
Location: net/core/dev.c:3044
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81893677)
Location: net/core/dev.c:3068
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b4097)
Location: net/core/dev.c:3312
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81900967)
Location: net/core/dev.c:3314
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81932c97)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_vlan(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a049b0)
Location: net/core/dev.c:3590
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81a049b0-ffffffff81a04afd: validate_xmit_vlan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_vlan(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05730)
Location: net/core/dev.c:3620
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81a05730-ffffffff81a05884: validate_xmit_vlan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_vlan(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ee0c0)
Location: net/core/dev.c:3688
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff819ee0c0-ffffffff819ee237: validate_xmit_vlan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_vlan(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9f360)
Location: net/core/dev.c:3618
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81a9f360-ffffffff81a9f4d7: validate_xmit_vlan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c18ec7)
Location: net/core/dev.c:3624
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc9e97)
Location: net/core/dev.c:3611
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3aa23)
Location: net/core/dev.c:3571
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef8dd3)
Location: net/core/dev.c:3581
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd0cc4)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ceb900)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000caed34)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075b332)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff818d2c97)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
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
In net/core/dev.c (ffffffff8188cb27)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81923c97)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81945107)
Location: net/core/dev.c:3232
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
