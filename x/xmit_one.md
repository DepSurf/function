# Function: <code>xmit_one</code>

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
In net/core/dev.c (ffffffff8171c85b)
Location: net/core/dev.c:2707
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817851b7)
Location: net/core/dev.c:2908
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff817b2837)
Location: net/core/dev.c:2905
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff817d0027)
Location: net/core/dev.c:2972
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81849977)
Location: net/core/dev.c:2999
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81893bd3)
Location: net/core/dev.c:3023
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff818b45e3)
Location: net/core/dev.c:3267
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81900f02)
Location: net/core/dev.c:3269
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81933232)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81a080b3)
Location: net/core/dev.c:3545
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81a04fc0)
Location: net/core/dev.c:3574
Inline: True
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81a04fc0-ffffffff81a0511e: xmit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff819ea2f0)
Location: net/core/dev.c:3642
Inline: True
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff819ea2f0-ffffffff819ea44e: xmit_one.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff81a9afd0)
Location: net/core/dev.c:3572
Inline: True
Direct callers:
  - net/core/dev.c:dev_hard_start_xmit
```
**Symbols:**

```
ffffffff81a9afd0-ffffffff81a9b128: xmit_one.constprop.0 (STB_LOCAL)
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
In net/core/dev.c (ffffffff81c19499)
Location: net/core/dev.c:3579
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81dca4a9)
Location: net/core/dev.c:3566
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81e3b029)
Location: net/core/dev.c:3526
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81ef9396)
Location: net/core/dev.c:3536
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffff800010bd1288)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (c0cebf00)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (c000000000caf55c)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffe00075b804)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff818d3232)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff8188d0c2)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81924232)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
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
In net/core/dev.c (ffffffff81945692)
Location: net/core/dev.c:3187
Inline: True
Inline callers:
  - net/core/dev.c:dev_hard_start_xmit
```
</details>
</li>
</ul>

## Differences
