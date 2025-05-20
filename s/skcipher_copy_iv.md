# Function: <code>skcipher_copy_iv</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f6956)
Location: crypto/skcipher.c:391
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff81402d3a)
Location: crypto/skcipher.c:392
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff8142b3a5)
Location: crypto/skcipher.c:392
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff8145e0be)
Location: crypto/skcipher.c:393
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff8147b958)
Location: crypto/skcipher.c:392
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff814a9cf6)
Location: crypto/skcipher.c:392
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff814c49e6)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skcipher_copy_iv(struct skcipher_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522630)
Location: crypto/skcipher.c:396
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_first
```
**Symbols:**

```
ffffffff81522630-ffffffff815226f3: skcipher_copy_iv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skcipher_copy_iv(struct skcipher_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153f4f0)
Location: crypto/skcipher.c:396
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_walk_first
```
**Symbols:**

```
ffffffff8153f4f0-ffffffff8153f5b3: skcipher_copy_iv (STB_LOCAL)
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
In crypto/skcipher.c (ffffffff815482c0)
Location: crypto/skcipher.c:397
Inline: True
Direct callers:
  - crypto/skcipher.c:skcipher_walk_first
```
**Symbols:**

```
ffffffff815482c0-ffffffff81548381: skcipher_copy_iv.constprop.0 (STB_LOCAL)
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
In crypto/skcipher.c (ffffffff815a8aa0)
Location: crypto/skcipher.c:397
Inline: True
Direct callers:
  - crypto/skcipher.c:skcipher_walk_first
```
**Symbols:**

```
ffffffff815a8aa0-ffffffff815a8b61: skcipher_copy_iv.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/skcipher.c (ffffffff8164ff10)
Location: crypto/skcipher.c:397
Inline: True
Direct callers:
  - crypto/skcipher.c:skcipher_walk_first
```
**Symbols:**

```
ffffffff8164ff10-ffffffff8164ffdd: skcipher_copy_iv.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/skcipher.c (ffffffff81709650)
Location: crypto/skcipher.c:397
Inline: True
Direct callers:
  - crypto/skcipher.c:skcipher_walk_first
```
**Symbols:**

```
ffffffff81709650-ffffffff8170971d: skcipher_copy_iv.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/skcipher.c (ffffffff81742e90)
Location: crypto/skcipher.c:415
Inline: True
Direct callers:
  - crypto/skcipher.c:skcipher_walk_first
```
**Symbols:**

```
ffffffff81742e90-ffffffff81742f5d: skcipher_copy_iv.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/skcipher.c (ffffffff81785190)
Location: crypto/skcipher.c:414
Inline: True
Direct callers:
  - crypto/skcipher.c:skcipher_walk_first
```
**Symbols:**

```
ffffffff81785190-ffffffff8178525d: skcipher_copy_iv.constprop.0 (STB_LOCAL)
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
In crypto/skcipher.c (ffff8000105bf440)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (c076d188)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (c000000000747120)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffe000404614)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff814bcfc6)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff814ad9e6)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff814b9056)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
In crypto/skcipher.c (ffffffff814d1b16)
Location: crypto/skcipher.c:396
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_first
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
</ul>
