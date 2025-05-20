# Function: <code>_extract_entropy</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81566300)
Location: drivers/char/random.c:1384
Inline: True
Direct callers:
  - drivers/char/random.c:extract_entropy
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff81566300-ffffffff8156643c: _extract_entropy.constprop.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81592a60)
Location: drivers/char/random.c:1384
Inline: True
Direct callers:
  - drivers/char/random.c:extract_entropy
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff81592a60-ffffffff81592b9c: _extract_entropy.constprop.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff815a6940)
Location: drivers/char/random.c:1364
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff815a6940-ffffffff815a6a92: _extract_entropy.constprop.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff8160d240)
Location: drivers/char/random.c:1363
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff8160d240-ffffffff8160d392: _extract_entropy.constprop.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1467
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff81646e30-ffffffff81646f79: _extract_entropy.constprop.37 (STB_LOCAL)
ffffffff816491b9-ffffffff816491c5: _extract_entropy.constprop.37.cold.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1476
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816652d0-ffffffff81665419: _extract_entropy.constprop.37 (STB_LOCAL)
ffffffff816674c5-ffffffff816674d1: _extract_entropy.constprop.37.cold.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff8169ad90-ffffffff8169aedb: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff8169cf60-ffffffff8169cf6c: _extract_entropy.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816bdac0-ffffffff816bdc0c: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff816bfcc4-ffffffff816bfcd0: _extract_entropy.constprop.0.cold (STB_LOCAL)
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
In drivers/char/random.c (0)
Location: drivers/char/random.c:1448
Inline: True
```
**Symbols:**

```
ffffffff81772080-ffffffff817721cc: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff81773b94-ffffffff81773ba0: _extract_entropy.constprop.0.cold (STB_LOCAL)
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
In drivers/char/random.c (0)
Location: drivers/char/random.c:1447
Inline: True
```
**Symbols:**

```
ffffffff8178d110-ffffffff8178d25c: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff81c08529-ffffffff81c08535: _extract_entropy.constprop.0.cold (STB_LOCAL)
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
In drivers/char/random.c (0)
Location: drivers/char/random.c:1423
Inline: True
Direct callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff817700e0-ffffffff81770228: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff81bfa0ee-ffffffff81bfa0fa: _extract_entropy.constprop.0.cold (STB_LOCAL)
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
In drivers/char/random.c (0)
Location: drivers/char/random.c:1443
Inline: True
Direct callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffff817f5ac0-ffffffff817f5c08: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff81cfaa1a-ffffffff81cfaa26: _extract_entropy.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffff8000108ae6f8)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffff8000108ae6f8-ffff8000108ae7d4: _extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (c09a9ebc)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
c09a9ebc-c09a9f8c: _extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (c0000000009468e0)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
c0000000009468e0-c000000000946a18: _extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffe000561c0c)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:rand_initialize
```
**Symbols:**

```
ffffffe000561c0c-ffffffe000561c92: _extract_entropy.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff81683530-ffffffff8168367c: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff81685714-ffffffff81685720: _extract_entropy.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816611b0-ffffffff816612fc: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff816633b4-ffffffff816633c0: _extract_entropy.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816b1900-ffffffff816b1a4c: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff816b3b04-ffffffff816b3b10: _extract_entropy.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1553
Inline: True
Direct callers:
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816cbda0-ffffffff816cbeec: _extract_entropy.constprop.0 (STB_LOCAL)
ffffffff816ce064-ffffffff816ce070: _extract_entropy.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
