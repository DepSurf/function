# Function: <code>clk_hw_register_fixed_factor_parent_hw</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor_parent_hw(struct device *dev, const char *name, const struct clk_hw *parent_hw, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff819ffdd0)
Location: drivers/clk/clk-fixed-factor.c:181
Inline: False
```
**Symbols:**

```
ffffffff819ffdd0-ffffffff819ffe06: clk_hw_register_fixed_factor_parent_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor_parent_hw(struct device *dev, const char *name, const struct clk_hw *parent_hw, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81a48aa0)
Location: drivers/clk/clk-fixed-factor.c:181
Inline: False
```
**Symbols:**

```
ffffffff81a48aa0-ffffffff81a48ad6: clk_hw_register_fixed_factor_parent_hw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor_parent_hw(struct device *dev, const char *name, const struct clk_hw *parent_hw, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81a94560)
Location: drivers/clk/clk-fixed-factor.c:181
Inline: False
```
**Symbols:**

```
ffffffff81a94560-ffffffff81a94596: clk_hw_register_fixed_factor_parent_hw (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
