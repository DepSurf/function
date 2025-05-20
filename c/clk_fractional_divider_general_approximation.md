# Function: <code>clk_fractional_divider_general_approximation</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void clk_fractional_divider_general_approximation(struct clk_hw *hw, long unsigned int rate, long unsigned int *parent_rate, long unsigned int *m, long unsigned int *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:104
Inline: False
```
**Symbols:**

```
ffffffff81cf3ba6-ffffffff81cf3c1d: clk_fractional_divider_general_approximation.cold (STB_LOCAL)
ffffffff8177e9d0-ffffffff8177ea8b: clk_fractional_divider_general_approximation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void clk_fractional_divider_general_approximation(struct clk_hw *hw, long unsigned int rate, long unsigned int *parent_rate, long unsigned int *m, long unsigned int *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:104
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
**Symbols:**

```
ffffffff81ebbe56-ffffffff81ebbecd: clk_fractional_divider_general_approximation.cold (STB_LOCAL)
ffffffff818b5870-ffffffff818b593e: clk_fractional_divider_general_approximation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void clk_fractional_divider_general_approximation(struct clk_hw *hw, long unsigned int rate, long unsigned int *parent_rate, long unsigned int *m, long unsigned int *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:116
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
**Symbols:**

```
ffffffff82093702-ffffffff82093779: clk_fractional_divider_general_approximation.cold (STB_LOCAL)
ffffffff81a02890-ffffffff81a0295e: clk_fractional_divider_general_approximation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void clk_fractional_divider_general_approximation(struct clk_hw *hw, long unsigned int rate, long unsigned int *parent_rate, long unsigned int *m, long unsigned int *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:120
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
**Symbols:**

```
ffffffff8211440e-ffffffff82114485: clk_fractional_divider_general_approximation.cold (STB_LOCAL)
ffffffff81a4b6e0-ffffffff81a4b7ae: clk_fractional_divider_general_approximation (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void clk_fractional_divider_general_approximation(struct clk_hw *hw, long unsigned int rate, long unsigned int *parent_rate, long unsigned int *m, long unsigned int *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:120
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_round_rate
```
**Symbols:**

```
ffffffff821f1bc5-ffffffff821f1c8c: clk_fractional_divider_general_approximation.cold (STB_LOCAL)
ffffffff81a96a20-ffffffff81a96b27: clk_fractional_divider_general_approximation (STB_GLOBAL)
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
