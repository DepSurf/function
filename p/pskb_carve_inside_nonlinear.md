# Function: <code>pskb_carve_inside_nonlinear</code>

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
In net/core/skbuff.c (ffffffff8176eecd)
Location: net/core/skbuff.c:4775
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
In net/core/skbuff.c (ffffffff8179c3bd)
Location: net/core/skbuff.c:4825
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
In net/core/skbuff.c (ffffffff817bd31f)
Location: net/core/skbuff.c:4919
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
In net/core/skbuff.c (ffffffff818356df)
Location: net/core/skbuff.c:5350
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
In net/core/skbuff.c (ffffffff8187fbf9)
Location: net/core/skbuff.c:5429
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
In net/core/skbuff.c (ffffffff818a086a)
Location: net/core/skbuff.c:5452
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
In net/core/skbuff.c (ffffffff818eb2ae)
Location: net/core/skbuff.c:5812
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
In net/core/skbuff.c (ffffffff8191d40e)
Location: net/core/skbuff.c:5829
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
int pskb_carve_inside_nonlinear(struct sk_buff *skb, const u32 off, int pos, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ef950)
Location: net/core/skbuff.c:5935
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
```
**Symbols:**

```
ffffffff819ef950-ffffffff819efceb: pskb_carve_inside_nonlinear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pskb_carve_inside_nonlinear(struct sk_buff *skb, const u32 off, int pos, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ef600)
Location: net/core/skbuff.c:6073
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
```
**Symbols:**

```
ffffffff819ef600-ffffffff819ef994: pskb_carve_inside_nonlinear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pskb_carve_inside_nonlinear(struct sk_buff *skb, const u32 off, int pos, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6161
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff819d7dd0-ffffffff819d8208: pskb_carve_inside_nonlinear (STB_LOCAL)
ffffffff81c22d2f-ffffffff81c22d43: pskb_carve_inside_nonlinear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pskb_carve_inside_nonlinear(struct sk_buff *skb, const u32 off, int pos, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6236
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81a87c20-ffffffff81a88058: pskb_carve_inside_nonlinear (STB_LOCAL)
ffffffff81d353b6-ffffffff81d353ca: pskb_carve_inside_nonlinear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pskb_carve_inside_nonlinear(struct sk_buff *skb, const u32 off, int pos, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6153
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81bfd060-ffffffff81bfd4e6: pskb_carve_inside_nonlinear (STB_LOCAL)
ffffffff81f018d8-ffffffff81f018ec: pskb_carve_inside_nonlinear.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pskb_carve_inside_nonlinear(struct sk_buff *skb, const u32 off, int pos, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dabfe0)
Location: net/core/skbuff.c:6354
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81dabfe0-ffffffff81dac4c1: pskb_carve_inside_nonlinear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pskb_carve_inside_nonlinear(struct sk_buff *skb, const u32 off, int pos, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1bde0)
Location: net/core/skbuff.c:6402
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81e1bde0-ffffffff81e1c43c: pskb_carve_inside_nonlinear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pskb_carve_inside_nonlinear(struct sk_buff *skb, const u32 off, int pos, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed94e0)
Location: net/core/skbuff.c:6549
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff81ed94e0-ffffffff81ed9b39: pskb_carve_inside_nonlinear (STB_LOCAL)
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
In net/core/skbuff.c (ffff800010bb7de4)
Location: net/core/skbuff.c:5829
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
In net/core/skbuff.c (c0cd49dc)
Location: net/core/skbuff.c:5829
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
In net/core/skbuff.c (c000000000c8fc20)
Location: net/core/skbuff.c:5829
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
In net/core/skbuff.c (ffffffe000747754)
Location: net/core/skbuff.c:5829
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
In net/core/skbuff.c (ffffffff818bd40e)
Location: net/core/skbuff.c:5829
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
In net/core/skbuff.c (ffffffff8187734e)
Location: net/core/skbuff.c:5829
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
In net/core/skbuff.c (ffffffff8190e40e)
Location: net/core/skbuff.c:5829
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
In net/core/skbuff.c (ffffffff8192f53e)
Location: net/core/skbuff.c:5829
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
