# Function: <code>pskb_carve_frag_list</code>

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
In net/core/skbuff.c (ffffffff8176f272)
Location: net/core/skbuff.c:4721
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
In net/core/skbuff.c (ffffffff8179c762)
Location: net/core/skbuff.c:4771
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
In net/core/skbuff.c (ffffffff817bd6e5)
Location: net/core/skbuff.c:4865
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
In net/core/skbuff.c (ffffffff81835afe)
Location: net/core/skbuff.c:5296
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
In net/core/skbuff.c (ffffffff8187ff3a)
Location: net/core/skbuff.c:5375
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
In net/core/skbuff.c (ffffffff818a0b8a)
Location: net/core/skbuff.c:5398
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
In net/core/skbuff.c (ffffffff818eb5c6)
Location: net/core/skbuff.c:5758
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
In net/core/skbuff.c (ffffffff8191d726)
Location: net/core/skbuff.c:5775
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:5881
Inline: True
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff819ef850-ffffffff819ef949: pskb_carve_frag_list.constprop.0 (STB_LOCAL)
ffffffff819f4a54-ffffffff819f4a6d: pskb_carve_frag_list.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6019
Inline: True
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
```
**Symbols:**

```
ffffffff819ef500-ffffffff819ef5f9: pskb_carve_frag_list.constprop.0 (STB_LOCAL)
ffffffff81c309cd-ffffffff81c309e6: pskb_carve_frag_list.constprop.0.cold (STB_LOCAL)
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
In net/core/skbuff.c (ffffffff819d809d)
Location: net/core/skbuff.c:6107
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81a87eed)
Location: net/core/skbuff.c:6182
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81bfd310)
Location: net/core/skbuff.c:6099
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81dac2ad)
Location: net/core/skbuff.c:6300
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81e1c139)
Location: net/core/skbuff.c:6348
Inline: True
Inline callers:
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
In net/core/skbuff.c (ffffffff81ed9836)
Location: net/core/skbuff.c:6495
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
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
In net/core/skbuff.c (ffff800010bb80d8)
Location: net/core/skbuff.c:5775
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
In net/core/skbuff.c (c0cd4cac)
Location: net/core/skbuff.c:5775
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
In net/core/skbuff.c (c000000000c90010)
Location: net/core/skbuff.c:5775
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
In net/core/skbuff.c (ffffffe0007479c2)
Location: net/core/skbuff.c:5775
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
In net/core/skbuff.c (ffffffff818bd726)
Location: net/core/skbuff.c:5775
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
In net/core/skbuff.c (ffffffff81877666)
Location: net/core/skbuff.c:5775
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
In net/core/skbuff.c (ffffffff8190e726)
Location: net/core/skbuff.c:5775
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
In net/core/skbuff.c (ffffffff8192f856)
Location: net/core/skbuff.c:5775
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
```
</details>
</li>
</ul>

## Differences
