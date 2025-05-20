# Function: <code>clk_fd_get_div</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void clk_fd_get_div(struct clk_hw *hw, struct u32_fract *fract);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:69
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_denominator_get
  - drivers/clk/clk-fractional-divider.c:clk_fd_numerator_get
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
**Symbols:**

```
ffffffff81a02650-ffffffff81a02703: clk_fd_get_div (STB_LOCAL)
ffffffff820936c3-ffffffff82093702: clk_fd_get_div.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void clk_fd_get_div(struct clk_hw *hw, struct u32_fract *fract);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:69
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_denominator_get
  - drivers/clk/clk-fractional-divider.c:clk_fd_numerator_get
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
**Symbols:**

```
ffffffff81a4b2e0-ffffffff81a4b3fd: clk_fd_get_div (STB_LOCAL)
ffffffff82114356-ffffffff8211440e: clk_fd_get_div.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void clk_fd_get_div(struct clk_hw *hw, struct u32_fract *fract);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:69
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_denominator_get
  - drivers/clk/clk-fractional-divider.c:clk_fd_numerator_get
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
**Symbols:**

```
ffffffff81a970c0-ffffffff81a971dd: clk_fd_get_div (STB_LOCAL)
ffffffff821f1db7-ffffffff821f1e6f: clk_fd_get_div.cold (STB_LOCAL)
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
