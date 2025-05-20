# Function: <code>kfree_skbmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705260)
Location: net/core/skbuff.c:616
Inline: False
Direct callers:
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:consume_skb
```
**Symbols:**

```
ffffffff81705260-ffffffff817052bb: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176be30)
Location: net/core/skbuff.c:617
Inline: False
Direct callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff8176be30-ffffffff8176be8b: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799010)
Location: net/core/skbuff.c:617
Inline: False
Direct callers:
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff81799010-ffffffff8179906b: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b87c0)
Location: net/core/skbuff.c:616
Inline: True
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff817b87c0-ffffffff817b881b: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182fc40)
Location: net/core/skbuff.c:576
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff8182fc40-ffffffff8182fca1: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a5c0)
Location: net/core/skbuff.c:576
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
**Symbols:**

```
ffffffff8187a5c0-ffffffff8187a621: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b1b0)
Location: net/core/skbuff.c:583
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
**Symbols:**

```
ffffffff8189b1b0-ffffffff8189b20e: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5390)
Location: net/core/skbuff.c:617
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff818e5390-ffffffff818e53ed: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917520)
Location: net/core/skbuff.c:617
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff81917520-ffffffff8191757d: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb9c0)
Location: net/core/skbuff.c:616
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
**Symbols:**

```
ffffffff819eb9c0-ffffffff819eba43: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb540)
Location: net/core/skbuff.c:630
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
**Symbols:**

```
ffffffff819eb540-ffffffff819eb5c3: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1cd0)
Location: net/core/skbuff.c:678
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
**Symbols:**

```
ffffffff819d1cd0-ffffffff819d1d53: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a818d0)
Location: net/core/skbuff.c:694
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
```
**Symbols:**

```
ffffffff81a818d0-ffffffff81a81953: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf5f80)
Location: net/core/skbuff.c:694
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:__consume_stateless_skb
```
**Symbols:**

```
ffffffff81bf5f80-ffffffff81bf602b: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da49c0)
Location: net/core/skbuff.c:868
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:kfree_skb_reason
```
**Symbols:**

```
ffffffff81da49c0-ffffffff81da4a6b: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e13640)
Location: net/core/skbuff.c:959
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
```
**Symbols:**

```
ffffffff81e13640-ffffffff81e136df: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed0670)
Location: net/core/skbuff.c:1045
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
```
**Symbols:**

```
ffffffff81ed0670-ffffffff81ed070f: kfree_skbmem (STB_LOCAL)
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
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb20d0)
Location: net/core/skbuff.c:617
Inline: True
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffff800010bb20d0-ffff800010bb2168: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccf7e8)
Location: net/core/skbuff.c:617
Inline: True
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
c0ccf7e8-c0ccf86c: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c89590)
Location: net/core/skbuff.c:617
Inline: True
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
c000000000c89590-c000000000c89678: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000743530)
Location: net/core/skbuff.c:617
Inline: True
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffe000743530-ffffffe0007435b6: kfree_skbmem (STB_LOCAL)
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
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7520)
Location: net/core/skbuff.c:617
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff818b7520-ffffffff818b757d: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871470)
Location: net/core/skbuff.c:617
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff81871470-ffffffff818714cd: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908520)
Location: net/core/skbuff.c:617
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff81908520-ffffffff8190857d: kfree_skbmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kfree_skbmem(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929500)
Location: net/core/skbuff.c:617
Inline: False
Direct callers:
  - net/core/skbuff.c:__consume_stateless_skb
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
```
**Symbols:**

```
ffffffff81929500-ffffffff8192955d: kfree_skbmem (STB_LOCAL)
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
