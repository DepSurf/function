# Function: <code>devm_clk_hw_get_clk</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk *devm_clk_hw_get_clk(struct device *dev, struct clk_hw *hw, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171adb0)
Location: drivers/clk/clk.c:4236
Inline: False
```
**Symbols:**

```
ffffffff8171adb0-ffffffff8171ae66: devm_clk_hw_get_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk *devm_clk_hw_get_clk(struct device *dev, struct clk_hw *hw, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81700b60)
Location: drivers/clk/clk.c:4245
Inline: False
```
**Symbols:**

```
ffffffff81700b60-ffffffff81700c03: devm_clk_hw_get_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk *devm_clk_hw_get_clk(struct device *dev, struct clk_hw *hw, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8177b370)
Location: drivers/clk/clk.c:4272
Inline: False
```
**Symbols:**

```
ffffffff8177b370-ffffffff8177b41a: devm_clk_hw_get_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk *devm_clk_hw_get_clk(struct device *dev, struct clk_hw *hw, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b1bb0)
Location: drivers/clk/clk.c:4345
Inline: False
```
**Symbols:**

```
ffffffff818b1bb0-ffffffff818b1c76: devm_clk_hw_get_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk *devm_clk_hw_get_clk(struct device *dev, struct clk_hw *hw, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fe1d0)
Location: drivers/clk/clk.c:4486
Inline: False
```
**Symbols:**

```
ffffffff819fe1d0-ffffffff819fe296: devm_clk_hw_get_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk *devm_clk_hw_get_clk(struct device *dev, struct clk_hw *hw, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a46e50)
Location: drivers/clk/clk.c:4545
Inline: False
```
**Symbols:**

```
ffffffff81a46e50-ffffffff81a46f16: devm_clk_hw_get_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk *devm_clk_hw_get_clk(struct device *dev, struct clk_hw *hw, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a928f0)
Location: drivers/clk/clk.c:4591
Inline: False
```
**Symbols:**

```
ffffffff81a928f0-ffffffff81a929b6: devm_clk_hw_get_clk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
