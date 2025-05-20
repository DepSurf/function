# Function: <code>validate_xmit_xfrm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81880050)
Location: net/xfrm/xfrm_device.c:26
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81880050-ffffffff8188012c: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81901160)
Location: net/xfrm/xfrm_device.c:26
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81901160-ffffffff81901248: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81957c60)
Location: net/xfrm/xfrm_device.c:26
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81957c60-ffffffff81957f57: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff8198cd40)
Location: net/xfrm/xfrm_device.c:26
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff8198cd40-ffffffff8198d048: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff819f8580)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff819f8580-ffffffff819f88b2: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81a2f1e0)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81a2f1e0-ffffffff81a2f512: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81b21df0)
Location: net/xfrm/xfrm_device.c:100
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81b21df0-ffffffff81b22129: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81b307d0)
Location: net/xfrm/xfrm_device.c:100
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81b307d0-ffffffff81b30b22: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81b1e500)
Location: net/xfrm/xfrm_device.c:100
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81b1e500-ffffffff81b1e856: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81be2ff0)
Location: net/xfrm/xfrm_device.c:100
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81be2ff0-ffffffff81be339a: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81d7a1f0)
Location: net/xfrm/xfrm_device.c:100
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81d7a1f0-ffffffff81d7a5a9: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81f47060)
Location: net/xfrm/xfrm_device.c:112
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81f47060-ffffffff81f474ad: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81fa6a80)
Location: net/xfrm/xfrm_device.c:113
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81fa6a80-ffffffff81fa6f78: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff82073d70)
Location: net/xfrm/xfrm_device.c:113
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff82073d70-ffffffff82074222: validate_xmit_xfrm (STB_GLOBAL)
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
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffff800010cee2e0)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffff800010cee2e0-ffff800010cee6c4: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (c0df6184)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
c0df6184-c0df650c: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (c000000000e12e90)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
c000000000e12e90-c000000000e13340: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffe00083b58a)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffe00083b58a-ffffffe00083b864: validate_xmit_xfrm (STB_GLOBAL)
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
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff819ce870)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff819ce870-ffffffff819ceba2: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff8198b650)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff8198b650-ffffffff8198b967: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81a392f0)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81a392f0-ffffffff81a39622: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *validate_xmit_xfrm(struct sk_buff *skb, netdev_features_t features, bool *again);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81a44d20)
Location: net/xfrm/xfrm_device.c:76
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
```
**Symbols:**

```
ffffffff81a44d20-ffffffff81a45052: validate_xmit_xfrm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct sk_buff *</code>
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
