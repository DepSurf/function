# Function: <code>divider_determine_rate</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int divider_determine_rate(struct clk_hw *hw, struct clk_rate_request *req, const struct clk_div_table *table, u8 width, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff8177c55a)
Location: drivers/clk/clk-divider.c:346
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_round_rate_parent
```
**Symbols:**

```
ffffffff8177c4c0-ffffffff8177c508: divider_determine_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int divider_determine_rate(struct clk_hw *hw, struct clk_rate_request *req, const struct clk_div_table *table, u8 width, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff818b2e97)
Location: drivers/clk/clk-divider.c:346
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_round_rate_parent
```
**Symbols:**

```
ffffffff818b2df0-ffffffff818b2e4a: divider_determine_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int divider_determine_rate(struct clk_hw *hw, struct clk_rate_request *req, const struct clk_div_table *table, u8 width, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff819ff637)
Location: drivers/clk/clk-divider.c:346
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_round_rate_parent
```
**Symbols:**

```
ffffffff819ff560-ffffffff819ff5bc: divider_determine_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int divider_determine_rate(struct clk_hw *hw, struct clk_rate_request *req, const struct clk_div_table *table, u8 width, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81a48307)
Location: drivers/clk/clk-divider.c:346
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_round_rate_parent
```
**Symbols:**

```
ffffffff81a48230-ffffffff81a4828c: divider_determine_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int divider_determine_rate(struct clk_hw *hw, struct clk_rate_request *req, const struct clk_div_table *table, u8 width, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81a93da7)
Location: drivers/clk/clk-divider.c:346
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:divider_round_rate_parent
```
**Symbols:**

```
ffffffff81a93cd0-ffffffff81a93d2c: divider_determine_rate (STB_GLOBAL)
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
