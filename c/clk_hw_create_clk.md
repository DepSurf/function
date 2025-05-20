# Function: <code>clk_hw_create_clk</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81630ca0)
Location: drivers/clk/clk.c:3466
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
```
**Symbols:**

```
ffffffff81630ca0-ffffffff81630d7c: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81652a60)
Location: drivers/clk/clk.c:3515
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
```
**Symbols:**

```
ffffffff81652a60-ffffffff81652b3c: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81702560)
Location: drivers/clk/clk.c:3605
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
```
**Symbols:**

```
ffffffff81702560-ffffffff817026da: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171ae08)
Location: drivers/clk/clk.c:3656
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_get_clk
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:devm_clk_hw_get_clk
```
**Symbols:**

```
ffffffff8171a510-ffffffff8171a63b: clk_hw_create_clk.part.0.isra.0 (STB_LOCAL)
ffffffff8171f990-ffffffff8171f9b8: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff817009b0)
Location: drivers/clk/clk.c:3665
Inline: True
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:devm_clk_hw_get_clk
```
**Symbols:**

```
ffffffff817009b0-ffffffff81700b26: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8177b1c0)
Location: drivers/clk/clk.c:3693
Inline: True
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:devm_clk_hw_get_clk
```
**Symbols:**

```
ffffffff8177b1c0-ffffffff8177b336: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b19c0)
Location: drivers/clk/clk.c:3765
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:devm_clk_hw_get_clk
```
**Symbols:**

```
ffffffff818b19c0-ffffffff818b1b49: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fdfc0)
Location: drivers/clk/clk.c:3954
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:devm_clk_hw_get_clk
```
**Symbols:**

```
ffffffff819fdfc0-ffffffff819fe149: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a46c40)
Location: drivers/clk/clk.c:4006
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:devm_clk_hw_get_clk
```
**Symbols:**

```
ffffffff81a46c40-ffffffff81a46dc9: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a92730)
Location: drivers/clk/clk.c:4052
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:devm_clk_hw_get_clk
```
**Symbols:**

```
ffffffff81a92730-ffffffff81a92862: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c35d8)
Location: drivers/clk/clk.c:3515
Inline: True
Inline callers:
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
```
**Symbols:**

```
ffff8000107bec60-ffff8000107bed24: clk_hw_create_clk.part.0 (STB_LOCAL)
ffff8000107c3398-ffff8000107c3408: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (c08eefcc)
Location: drivers/clk/clk.c:3515
Inline: True
Inline callers:
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
```
**Symbols:**

```
c08eb314-c08eb3b0: clk_hw_create_clk.part.0 (STB_LOCAL)
c08eedc8-c08eedfc: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffe000510f5a)
Location: drivers/clk/clk.c:3515
Inline: True
Inline callers:
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
Direct callers:
  - drivers/clk/clkdev.c:clk_get
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:__of_clk_get
  - drivers/clk/clk.c:of_clk_get_from_provider
```
**Symbols:**

```
ffffffe00050dff2-ffffffe00050e09e: clk_hw_create_clk.part.0 (STB_LOCAL)
ffffffe000510d98-ffffffe000510df6: clk_hw_create_clk (STB_GLOBAL)
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
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81618ac0)
Location: drivers/clk/clk.c:3515
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
```
**Symbols:**

```
ffffffff81618ac0-ffffffff81618b9c: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160cff0)
Location: drivers/clk/clk.c:3515
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
```
**Symbols:**

```
ffffffff8160cff0-ffffffff8160d0cc: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816468a0)
Location: drivers/clk/clk.c:3515
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
```
**Symbols:**

```
ffffffff816468a0-ffffffff8164697c: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk *clk_hw_create_clk(struct device *dev, struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81660e30)
Location: drivers/clk/clk.c:3515
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:__clk_get_sys
```
**Symbols:**

```
ffffffff81660e30-ffffffff81660f0c: clk_hw_create_clk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
