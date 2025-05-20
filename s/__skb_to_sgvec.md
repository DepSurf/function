# Function: <code>__skb_to_sgvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81705700)
Location: net/core/skbuff.c:3414
Inline: False
Direct callers:
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
```
**Symbols:**

```
ffffffff81705700-ffffffff81705955: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c3c0)
Location: net/core/skbuff.c:3455
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff8176c3c0-ffffffff8176c622: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799e00)
Location: net/core/skbuff.c:3481
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81799e00-ffffffff8179a064: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b9470)
Location: net/core/skbuff.c:3522
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff817b9470-ffffffff817b9717: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81831cb0)
Location: net/core/skbuff.c:3906
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81831cb0-ffffffff81831f61: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187c380)
Location: net/core/skbuff.c:3945
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff8187c380-ffffffff8187c627: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189cd10)
Location: net/core/skbuff.c:3965
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff8189cd10-ffffffff8189cfaa: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:4150
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff818e74e0-ffffffff818e775c: __skb_to_sgvec (STB_LOCAL)
ffffffff818ef14a-ffffffff818ef1a3: __skb_to_sgvec.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81919810)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81919810-ffffffff81919a6c: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea6d0)
Location: net/core/skbuff.c:4264
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff819ea6d0-ffffffff819ea93a: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea410)
Location: net/core/skbuff.c:4331
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff819ea410-ffffffff819ea67a: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d09d0)
Location: net/core/skbuff.c:4417
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff819d09d0-ffffffff819d0c3a: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a7fb80)
Location: net/core/skbuff.c:4485
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81a7fb80-ffffffff81a7fde8: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4080)
Location: net/core/skbuff.c:4401
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81bf4080-ffffffff81bf4301: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da1e90)
Location: net/core/skbuff.c:4603
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81da1e90-ffffffff81da2111: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e106e0)
Location: net/core/skbuff.c:4794
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81e106e0-ffffffff81e109eb: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecd200)
Location: net/core/skbuff.c:4920
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81ecd200-ffffffff81ecd50b: __skb_to_sgvec (STB_LOCAL)
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
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb28c0)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffff800010bb28c0-ffff800010bb2b38: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd0dc0)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
c0cd0dc0-c0cd105c: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8a8e0)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
c000000000c8a8e0-c000000000c8ac98: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000743de4)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffe000743de4-ffffffe000743fce: __skb_to_sgvec (STB_LOCAL)
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
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b9810)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff818b9810-ffffffff818b9a6c: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81873760)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff81873760-ffffffff818739bc: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190a810)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff8190a810-ffffffff8190aa6c: __skb_to_sgvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __skb_to_sgvec(struct sk_buff *skb, struct scatterlist *sg, int offset, int len, unsigned int recursion_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192b910)
Location: net/core/skbuff.c:4162
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_to_sgvec_nomark
  - net/core/skbuff.c:skb_to_sgvec
  - net/core/skbuff.c:__skb_to_sgvec
```
**Symbols:**

```
ffffffff8192b910-ffffffff8192bb6c: __skb_to_sgvec (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int recursion_level</code>
</li>
</ul>
</details>
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
