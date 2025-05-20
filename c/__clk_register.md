# Function: <code>__clk_register</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3588
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff8162fa80-ffffffff8162fc9a: __clk_register (STB_LOCAL)
ffffffff81630fb9-ffffffff81630fd1: __clk_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81651e60)
Location: drivers/clk/clk.c:3637
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff81651e60-ffffffff81652243: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81700f40)
Location: drivers/clk/clk.c:3727
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff81700f40-ffffffff817011c1: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171e460)
Location: drivers/clk/clk.c:3796
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff8171e460-ffffffff8171e6e1: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ff4b0)
Location: drivers/clk/clk.c:3805
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff816ff4b0-ffffffff816ff731: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81779ca0)
Location: drivers/clk/clk.c:3833
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff81779ca0-ffffffff81779f1e: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b00d0)
Location: drivers/clk/clk.c:3906
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff818b00d0-ffffffff818b0354: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fc580)
Location: drivers/clk/clk.c:4095
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff819fc580-ffffffff819fc804: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a44ff0)
Location: drivers/clk/clk.c:4147
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff81a44ff0-ffffffff81a45274: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a90b00)
Location: drivers/clk/clk.c:4193
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff81a90b00-ffffffff81a90d6a: __clk_register (STB_LOCAL)
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
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c29f8)
Location: drivers/clk/clk.c:3637
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_hw_register
  - drivers/clk/clk.c:clk_hw_register
  - drivers/clk/clk.c:clk_hw_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffff8000107c29f8-ffff8000107c2d58: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ed654)
Location: drivers/clk/clk.c:3637
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_hw_register
  - drivers/clk/clk.c:clk_hw_register
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
c08ed654-c08ed9f4: __clk_register (STB_LOCAL)
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
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe000510446)
Location: drivers/clk/clk.c:3637
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_hw_register
  - drivers/clk/clk.c:clk_hw_register
  - drivers/clk/clk.c:clk_hw_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffe000510446-ffffffe000510770: __clk_register (STB_LOCAL)
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
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81617ec0)
Location: drivers/clk/clk.c:3637
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff81617ec0-ffffffff816182a3: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160c3f0)
Location: drivers/clk/clk.c:3637
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff8160c3f0-ffffffff8160c7d3: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81645ca0)
Location: drivers/clk/clk.c:3637
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff81645ca0-ffffffff81646083: __clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk *__clk_register(struct device *dev, struct device_node *np, struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81660230)
Location: drivers/clk/clk.c:3637
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk.c:of_clk_hw_register
```
**Symbols:**

```
ffffffff81660230-ffffffff81660613: __clk_register (STB_LOCAL)
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
