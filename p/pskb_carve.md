# Function: <code>pskb_carve</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176ee90)
Location: net/core/skbuff.c:4857
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff8176ee90-ffffffff8176f48e: pskb_carve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179c380)
Location: net/core/skbuff.c:4907
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff8179c380-ffffffff8179c97e: pskb_carve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bd2d0)
Location: net/core/skbuff.c:5001
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff817bd2d0-ffffffff817bd888: pskb_carve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81835690)
Location: net/core/skbuff.c:5432
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff81835690-ffffffff81835c90: pskb_carve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5511
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff8187fa50-ffffffff818800a3: pskb_carve (STB_LOCAL)
ffffffff818834a4-ffffffff818834b7: pskb_carve.cold.87 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5534
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff818a06d0-ffffffff818a0ced: pskb_carve (STB_LOCAL)
ffffffff818a3ef5-ffffffff818a3f08: pskb_carve.cold.88 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5894
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff818eb110-ffffffff818eb6da: pskb_carve (STB_LOCAL)
ffffffff818ef1f8-ffffffff818ef20c: pskb_carve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff8191d270-ffffffff8191d83a: pskb_carve (STB_LOCAL)
ffffffff8192119d-ffffffff819211b1: pskb_carve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f33b9)
Location: net/core/skbuff.c:6021
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f33e9)
Location: net/core/skbuff.c:6158
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d9649)
Location: net/core/skbuff.c:6246
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a89609)
Location: net/core/skbuff.c:6321
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
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
In net/core/skbuff.c (ffffffff81bfe942)
Location: net/core/skbuff.c:6234
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
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
In net/core/skbuff.c (ffffffff81dad372)
Location: net/core/skbuff.c:6434
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
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
In net/core/skbuff.c (ffffffff81e1d272)
Location: net/core/skbuff.c:6479
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
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
In net/core/skbuff.c (ffffffff81eda962)
Location: net/core/skbuff.c:6626
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
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
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb7c68)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffff800010bb7c68-ffff800010bb81e0: pskb_carve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd4860)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
c0cd4860-c0cd4db8: pskb_carve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8fa40)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
c000000000c8fa40-c000000000c9016c: pskb_carve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074761e)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffe00074761e-ffffffe000747a8e: pskb_carve (STB_LOCAL)
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
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff818bd270-ffffffff818bd83a: pskb_carve (STB_LOCAL)
ffffffff818c119d-ffffffff818c11b1: pskb_carve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff818771b0-ffffffff8187777a: pskb_carve (STB_LOCAL)
ffffffff8187b0dd-ffffffff8187b0f1: pskb_carve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff8190e270-ffffffff8190e83a: pskb_carve (STB_LOCAL)
ffffffff8191219d-ffffffff819121b1: pskb_carve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pskb_carve(struct sk_buff *skb, const u32 len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5911
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_extract
  - net/core/skbuff.c:pskb_carve
```
**Symbols:**

```
ffffffff8192f3a0-ffffffff8192f96a: pskb_carve (STB_LOCAL)
ffffffff8193333a-ffffffff8193334e: pskb_carve.cold (STB_LOCAL)
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
