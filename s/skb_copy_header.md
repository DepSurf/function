# Function: <code>skb_copy_header</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187bfd0)
Location: net/core/skbuff.c:1306
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff8187bfd0-ffffffff8187c05f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189c200)
Location: net/core/skbuff.c:1316
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff8189c200-ffffffff8189c28f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e6a80)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff818e6a80-ffffffff818e6b0f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81918bd0)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81918bd0-ffffffff81918c5f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ecae0)
Location: net/core/skbuff.c:1474
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff819ecae0-ffffffff819ecb6f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ec7a0)
Location: net/core/skbuff.c:1485
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff819ec7a0-ffffffff819ec82f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d2c90)
Location: net/core/skbuff.c:1527
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff819d2c90-ffffffff819d2d1f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a82890)
Location: net/core/skbuff.c:1548
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81a82890-ffffffff81a8291f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf72f0)
Location: net/core/skbuff.c:1542
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:bounce_skb
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81bf72f0-ffffffff81bf738d: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da6320)
Location: net/core/skbuff.c:1741
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81da6320-ffffffff81da63bd: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e15410)
Location: net/core/skbuff.c:1893
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81e15410-ffffffff81e154ad: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed27b0)
Location: net/core/skbuff.c:1981
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81ed27b0-ffffffff81ed284d: skb_copy_header (STB_GLOBAL)
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
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb48e0)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffff800010bb48e0-ffff800010bb4974: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd07b8)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
c0cd07b8-c0cd080c: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87ca0)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
c000000000c87ca0-c000000000c87d48: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074257c)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffe00074257c-ffffffe0007425f8: skb_copy_header (STB_GLOBAL)
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
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b8bd0)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff818b8bd0-ffffffff818b8c5f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81872b20)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81872b20-ffffffff81872baf: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81909bd0)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81909bd0-ffffffff81909c5f: skb_copy_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_copy_header(struct sk_buff *new, const struct sk_buff *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192acd0)
Location: net/core/skbuff.c:1475
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff8192acd0-ffffffff8192ad5f: skb_copy_header (STB_GLOBAL)
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
