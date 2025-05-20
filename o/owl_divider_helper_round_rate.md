# Function: <code>owl_divider_helper_round_rate</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int owl_divider_helper_round_rate(struct owl_clk_common *common, const struct owl_divider_hw *div_hw, long unsigned int rate, long unsigned int *parent_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-divider.c (ffff8000107c9f08)
Location: drivers/clk/actions/owl-divider.c:16
Inline: False
Direct callers:
  - drivers/clk/actions/owl-divider.c:owl_divider_round_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_div_round_rate
```
**Symbols:**

```
ffff8000107c9f08-ffff8000107c9f80: owl_divider_helper_round_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int owl_divider_helper_round_rate(struct owl_clk_common *common, const struct owl_divider_hw *div_hw, long unsigned int rate, long unsigned int *parent_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-divider.c (c08f5d18)
Location: drivers/clk/actions/owl-divider.c:16
Inline: False
Direct callers:
  - drivers/clk/actions/owl-divider.c:owl_divider_round_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_div_round_rate
```
**Symbols:**

```
c08f5d18-c08f5d74: owl_divider_helper_round_rate (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
