# Function: <code>dev_queue_xmit_nit</code>

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
In net/core/dev.c (ffffffff8171c89c)
Location: net/core/dev.c:1835
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81781340)
Location: net/core/dev.c:1855
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81781340-ffffffff8178154d: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ae930)
Location: net/core/dev.c:1871
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff817ae930-ffffffff817aeb3d: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cd2a0)
Location: net/core/dev.c:1905
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff817cd2a0-ffffffff817cd4a7: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818472a0)
Location: net/core/dev.c:1920
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff818472a0-ffffffff81847506: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1964
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81899053-ffffffff81899076: dev_queue_xmit_nit.cold.161 (STB_LOCAL)
ffffffff818918f0-ffffffff81891b40: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2009
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff818bb41c-ffffffff818bb43f: dev_queue_xmit_nit.cold.164 (STB_LOCAL)
ffffffff818b1100-ffffffff818b1354: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2019
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81907304-ffffffff81907329: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff818fdc20-ffffffff818fde96: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81939951-ffffffff81939976: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff8192ff50-ffffffff819301c6: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2297
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81a0ee94-ffffffff81a0eeb8: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81a03020-ffffffff81a032c3: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2322
Inline: False
```
**Symbols:**

```
ffffffff81c31170-ffffffff81c31194: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81a037e0-ffffffff81a03a7b: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2387
Inline: False
```
**Symbols:**

```
ffffffff81c23475-ffffffff81c23499: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff819ea050-ffffffff819ea2e5: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2262
Inline: False
```
**Symbols:**

```
ffffffff81d3600c-ffffffff81d3604b: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81a9ad30-ffffffff81a9afcf: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2239
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81f02819-ffffffff81f02858: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81c139e0-ffffffff81c13c98: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2224
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff820ab3f1-ffffffff820ab40c: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81dc3060-ffffffff81dc3335: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2250
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff8212ca3b-ffffffff8212ca56: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81e325d0-ffffffff81e328a5: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:2254
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff8220e77a-ffffffff8220e795: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81ef0a90-ffffffff81ef0d6c: dev_queue_xmit_nit (STB_GLOBAL)
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
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc9f88)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffff800010bc9f88-ffff800010bca1e0: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce8068)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
c0ce8068-c0ce82e4: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca9e70)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
c000000000ca9e70-c000000000caa1b0: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007579f0)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffe0007579f0-ffffffe000757bd8: dev_queue_xmit_nit (STB_GLOBAL)
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
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff818d9921-ffffffff818d9946: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff818cff50-ffffffff818d01c6: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81893761-ffffffff81893786: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff8188a010-ffffffff8188a286: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff8192a951-ffffffff8192a976: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81920f50-ffffffff819211c6: dev_queue_xmit_nit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dev_queue_xmit_nit(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1937
Inline: False
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff8194c09b-ffffffff8194c0c0: dev_queue_xmit_nit.cold (STB_LOCAL)
ffffffff81942e30-ffffffff819430a6: dev_queue_xmit_nit (STB_GLOBAL)
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
