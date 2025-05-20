# Function: <code>hw_to_owl_clk_common</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-gate.c (ffff8000107c9d00)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-gate.c:owl_gate_is_enabled
  - drivers/clk/actions/owl-gate.c:owl_gate_enable
  - drivers/clk/actions/owl-gate.c:owl_gate_disable
```
```
In drivers/clk/actions/owl-mux.c (ffff8000107c9eec)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-mux.c:owl_mux_set_parent
  - drivers/clk/actions/owl-mux.c:owl_mux_get_parent
```
```
In drivers/clk/actions/owl-divider.c (ffff8000107ca1a4)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-divider.c:owl_divider_set_rate
  - drivers/clk/actions/owl-divider.c:owl_divider_recalc_rate
  - drivers/clk/actions/owl-divider.c:owl_divider_round_rate
```
```
In drivers/clk/actions/owl-factor.c (ffff8000107ca6d4)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-factor.c:owl_factor_set_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_recalc_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_round_rate
```
```
In drivers/clk/actions/owl-composite.c (ffff8000107ca764)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-composite.c:owl_comp_fix_fact_recalc_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fix_fact_round_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fact_set_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fact_recalc_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fact_round_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_div_set_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_div_recalc_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_div_round_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_is_enabled
  - drivers/clk/actions/owl-composite.c:owl_comp_enable
  - drivers/clk/actions/owl-composite.c:owl_comp_disable
  - drivers/clk/actions/owl-composite.c:owl_comp_set_parent
  - drivers/clk/actions/owl-composite.c:owl_comp_get_parent
```
```
In drivers/clk/actions/owl-pll.c (ffff8000107cab1c)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-pll.c:owl_pll_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_disable
  - drivers/clk/actions/owl-pll.c:owl_pll_enable
  - drivers/clk/actions/owl-pll.c:owl_pll_is_enabled
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/actions/owl-gate.c (c08f5b34)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-gate.c:owl_gate_is_enabled
  - drivers/clk/actions/owl-gate.c:owl_gate_enable
  - drivers/clk/actions/owl-gate.c:owl_gate_disable
```
```
In drivers/clk/actions/owl-mux.c (c08f5d04)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-mux.c:owl_mux_set_parent
  - drivers/clk/actions/owl-mux.c:owl_mux_get_parent
```
```
In drivers/clk/actions/owl-divider.c (c08f5f40)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-divider.c:owl_divider_set_rate
  - drivers/clk/actions/owl-divider.c:owl_divider_recalc_rate
  - drivers/clk/actions/owl-divider.c:owl_divider_round_rate
```
```
In drivers/clk/actions/owl-factor.c (c08f6440)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-factor.c:owl_factor_set_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_recalc_rate
  - drivers/clk/actions/owl-factor.c:owl_factor_round_rate
```
```
In drivers/clk/actions/owl-composite.c (c08f6498)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-composite.c:owl_comp_fix_fact_recalc_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fix_fact_round_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fact_set_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fact_recalc_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_fact_round_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_div_set_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_div_recalc_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_div_round_rate
  - drivers/clk/actions/owl-composite.c:owl_comp_is_enabled
  - drivers/clk/actions/owl-composite.c:owl_comp_enable
  - drivers/clk/actions/owl-composite.c:owl_comp_disable
  - drivers/clk/actions/owl-composite.c:owl_comp_set_parent
  - drivers/clk/actions/owl-composite.c:owl_comp_get_parent
```
```
In drivers/clk/actions/owl-pll.c (c08f67c0)
Location: drivers/clk/actions/owl-common.h:35
Inline: True
Inline callers:
  - drivers/clk/actions/owl-pll.c:owl_pll_set_rate
  - drivers/clk/actions/owl-pll.c:owl_pll_disable
  - drivers/clk/actions/owl-pll.c:owl_pll_enable
  - drivers/clk/actions/owl-pll.c:owl_pll_is_enabled
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
