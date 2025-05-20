# Function: <code>owl_factor_helper_recalc_rate</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int owl_factor_helper_recalc_rate(struct owl_clk_common *common, const struct owl_factor_hw *factor_hw, long unsigned int parent_rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-factor.c (ffff8000107ca438)
Location: drivers/clk/actions/owl-factor.c:144
Inline: True
Direct callers:
  - drivers/clk/actions/owl-factor.c:owl_factor_recalc_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fact_recalc_rate
```
**Symbols:**

```
ffff8000107ca438-ffff8000107ca538: owl_factor_helper_recalc_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int owl_factor_helper_recalc_rate(struct owl_clk_common *common, const struct owl_factor_hw *factor_hw, long unsigned int parent_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-factor.c (c08f6210)
Location: drivers/clk/actions/owl-factor.c:144
Inline: False
Direct callers:
  - drivers/clk/actions/owl-factor.c:owl_factor_recalc_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fact_recalc_rate
```
**Symbols:**

```
c08f6210-c08f6340: owl_factor_helper_recalc_rate (STB_GLOBAL)
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
