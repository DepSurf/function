# Function: <code>devm_clk_hw_register_fixed_factor</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk_hw *devm_clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81701fc0)
Location: drivers/clk/clk-fixed-factor.c:181
Inline: False
```
**Symbols:**

```
ffffffff81701fc0-ffffffff81701fd2: devm_clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk_hw *devm_clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff8177cb50)
Location: drivers/clk/clk-fixed-factor.c:181
Inline: False
```
**Symbols:**

```
ffffffff8177cb50-ffffffff8177cb62: devm_clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk_hw *devm_clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff818b3520)
Location: drivers/clk/clk-fixed-factor.c:203
Inline: False
```
**Symbols:**

```
ffffffff818b3520-ffffffff818b3551: devm_clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *devm_clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff819ffd30)
Location: drivers/clk/clk-fixed-factor.c:238
Inline: False
```
**Symbols:**

```
ffffffff819ffd30-ffffffff819ffd63: devm_clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *devm_clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81a48a00)
Location: drivers/clk/clk-fixed-factor.c:238
Inline: False
```
**Symbols:**

```
ffffffff81a48a00-ffffffff81a48a33: devm_clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *devm_clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81a944c0)
Location: drivers/clk/clk-fixed-factor.c:238
Inline: False
```
**Symbols:**

```
ffffffff81a944c0-ffffffff81a944f3: devm_clk_hw_register_fixed_factor (STB_GLOBAL)
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
