# Function: <code>skb_zerocopy_clone</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81834bd0)
Location: net/core/skbuff.c:1138
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff81834bd0-ffffffff81834cc9: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187ee40)
Location: net/core/skbuff.c:1139
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff8187ee40-ffffffff8187ef3f: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189fc30)
Location: net/core/skbuff.c:1148
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff8189fc30-ffffffff8189fd2f: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ea650)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff818ea650-ffffffff818ea760: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191c7c0)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff8191c7c0-ffffffff8191c8d0: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eea70)
Location: net/core/skbuff.c:1306
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff819eea70-ffffffff819eebb0: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ee710)
Location: net/core/skbuff.c:1317
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff819ee710-ffffffff819ee850: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d4110)
Location: net/core/skbuff.c:1359
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff819d4110-ffffffff819d424c: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a83e30)
Location: net/core/skbuff.c:1380
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff81a83e30-ffffffff81a83f6c: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf9780)
Location: net/core/skbuff.c:1374
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff81bf9780-ffffffff81bf98bd: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da85d0)
Location: net/core/skbuff.c:1572
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff81da85d0-ffffffff81da870d: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e17270)
Location: net/core/skbuff.c:1716
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff81e17270-ffffffff81e173ad: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed4670)
Location: net/core/skbuff.c:1804
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff81ed4670-ffffffff81ed47ad: skb_zerocopy_clone (STB_LOCAL)
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
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb6d90)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffff800010bb6d90-ffff800010bb6eb4: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd3bec)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
c0cd3bec-c0cd3d18: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8e770)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
c000000000c8e770-c000000000c8e904: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe0007469e4)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffe0007469e4-ffffffe000746ac4: skb_zerocopy_clone (STB_LOCAL)
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
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bc7c0)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff818bc7c0-ffffffff818bc8d0: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81876700)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff81876700-ffffffff81876810: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190d7c0)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff8190d7c0-ffffffff8190d8d0: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_zerocopy_clone(struct sk_buff *nskb, struct sk_buff *orig, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192e8f0)
Location: net/core/skbuff.c:1307
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_copy_fclone
```
**Symbols:**

```
ffffffff8192e8f0-ffffffff8192ea00: skb_zerocopy_clone (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
