# Function: <code>clk_mux_determine_rate_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e5fa0)
Location: drivers/clk/clk.c:454
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
```
**Symbols:**

```
ffffffff816e5fa0-ffffffff816e61f1: clk_mux_determine_rate_flags.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81749f30)
Location: drivers/clk/clk.c:355
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
```
**Symbols:**

```
ffffffff81749f30-ffffffff8174a190: clk_mux_determine_rate_flags.isra.14 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff815327b0)
Location: drivers/clk/clk.c:355
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
```
**Symbols:**

```
ffffffff815327b0-ffffffff81532a10: clk_mux_determine_rate_flags.isra.16 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81546c30)
Location: drivers/clk/clk.c:355
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
```
**Symbols:**

```
ffffffff81546c30-ffffffff81546e73: clk_mux_determine_rate_flags.isra.16 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff815aa640)
Location: drivers/clk/clk.c:409
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
```
**Symbols:**

```
ffffffff815aa640-ffffffff815aa883: clk_mux_determine_rate_flags.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e18f0)
Location: drivers/clk/clk.c:428
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff815e18f0-ffffffff815e1b2d: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fba60)
Location: drivers/clk/clk.c:426
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff815fba60-ffffffff815fbc9d: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162dfb0)
Location: drivers/clk/clk.c:541
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff8162dfb0-ffffffff8162e1f3: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164fcc0)
Location: drivers/clk/clk.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff8164fcc0-ffffffff8164ff03: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fd7f0)
Location: drivers/clk/clk.c:551
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff816fd7f0-ffffffff816fda33: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171a910)
Location: drivers/clk/clk.c:545
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff8171a910-ffffffff8171ab53: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fbab0)
Location: drivers/clk/clk.c:545
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff816fbab0-ffffffff816fbce7: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81776270)
Location: drivers/clk/clk.c:545
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff81776270-ffffffff817764a7: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818acb20)
Location: drivers/clk/clk.c:539
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff818acb20-ffffffff818acd78: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fabf0)
Location: drivers/clk/clk.c:586
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff819fabf0-ffffffff819faf9b: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a43220)
Location: drivers/clk/clk.c:638
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff81a43220-ffffffff81a43483: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8ed30)
Location: drivers/clk/clk.c:638
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff81a8ed30-ffffffff81a8ef93: clk_mux_determine_rate_flags (STB_GLOBAL)
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
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bf168)
Location: drivers/clk/clk.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_mux_determine_rate
```
**Symbols:**

```
ffff8000107bf168-ffff8000107bf370: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08eb9d0)
Location: drivers/clk/clk.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
  - drivers/clk/meson/clk-regmap.c:clk_regmap_mux_determine_rate
```
**Symbols:**

```
c08eb9d0-c08ebc04: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050e50c)
Location: drivers/clk/clk.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffe00050e50c-ffffffe00050e6c0: clk_mux_determine_rate_flags (STB_GLOBAL)
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
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81615d20)
Location: drivers/clk/clk.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff81615d20-ffffffff81615f63: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160a250)
Location: drivers/clk/clk.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff8160a250-ffffffff8160a493: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81643b00)
Location: drivers/clk/clk.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff81643b00-ffffffff81643d43: clk_mux_determine_rate_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clk_mux_determine_rate_flags(struct clk_hw *hw, struct clk_rate_request *req, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165df40)
Location: drivers/clk/clk.c:547
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_mux_determine_rate_closest
  - drivers/clk/clk.c:__clk_mux_determine_rate
  - drivers/clk/clk-mux.c:clk_mux_determine_rate
```
**Symbols:**

```
ffffffff8165df40-ffffffff8165e183: clk_mux_determine_rate_flags (STB_GLOBAL)
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
