# Function: <code>pskb_carve_inside_header</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176f10b)
Location: net/core/skbuff.c:4652
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff8179c5fb)
Location: net/core/skbuff.c:4702
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff817bd526)
Location: net/core/skbuff.c:4796
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff81835902)
Location: net/core/skbuff.c:5227
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff8187fa99)
Location: net/core/skbuff.c:5306
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff818a0710)
Location: net/core/skbuff.c:5329
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff818eb153)
Location: net/core/skbuff.c:5689
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff8191d2b3)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pskb_carve_inside_header(struct sk_buff *skb, const u32 off, const int headlen, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ef5c0)
Location: net/core/skbuff.c:5812
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
```
**Symbols:**

```
ffffffff819ef5c0-ffffffff819ef841: pskb_carve_inside_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pskb_carve_inside_header(struct sk_buff *skb, const u32 off, const int headlen, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ef270)
Location: net/core/skbuff.c:5950
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
```
**Symbols:**

```
ffffffff819ef270-ffffffff819ef4f1: pskb_carve_inside_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pskb_carve_inside_header(struct sk_buff *skb, const u32 off, const int headlen, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d5050)
Location: net/core/skbuff.c:6038
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff819d5050-ffffffff819d52bf: pskb_carve_inside_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pskb_carve_inside_header(struct sk_buff *skb, const u32 off, const int headlen, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a84df0)
Location: net/core/skbuff.c:6113
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81a84df0-ffffffff81a8504c: pskb_carve_inside_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pskb_carve_inside_header(struct sk_buff *skb, const u32 off, const int headlen, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfadb0)
Location: net/core/skbuff.c:6034
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81bfadb0-ffffffff81bfb045: pskb_carve_inside_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pskb_carve_inside_header(struct sk_buff *skb, const u32 off, const int headlen, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da9a80)
Location: net/core/skbuff.c:6236
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81da9a80-ffffffff81da9d0d: pskb_carve_inside_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pskb_carve_inside_header(struct sk_buff *skb, const u32 off, const int headlen, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e187c0)
Location: net/core/skbuff.c:6287
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81e187c0-ffffffff81e18a83: pskb_carve_inside_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pskb_carve_inside_header(struct sk_buff *skb, const u32 off, const int headlen, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed5c60)
Location: net/core/skbuff.c:6434
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81ed5c60-ffffffff81ed5f20: pskb_carve_inside_header (STB_LOCAL)
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
In net/core/skbuff.c (ffff800010bb7cb4)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (c0cd48b4)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (c000000000c8fab8)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffe00074766c)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff818bd2b3)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff818771f3)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff8190e2b3)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
In net/core/skbuff.c (ffffffff8192f3e3)
Location: net/core/skbuff.c:5706
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
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
