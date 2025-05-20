# Function: <code>ti_clk_get_reg_addr</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ti_clk_get_reg_addr(struct device_node *node, int index, struct clk_omap_reg *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/ti/clk.c (c0915a40)
Location: drivers/clk/ti/clk.c:263
Inline: False
Direct callers:
  - drivers/clk/ti/autoidle.c:of_ti_clk_autoidle_setup
  - drivers/clk/ti/dpll.c:of_ti_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_dpll_setup
  - drivers/clk/ti/divider.c:ti_clk_divider_populate
  - drivers/clk/ti/gate.c:_of_ti_composite_gate_clk_setup
  - drivers/clk/ti/gate.c:_of_ti_gate_clk_setup
  - drivers/clk/ti/mux.c:of_ti_composite_mux_clk_setup
  - drivers/clk/ti/mux.c:of_mux_clk_setup
  - drivers/clk/ti/apll.c:of_omap2_apll_setup
  - drivers/clk/ti/apll.c:of_omap2_apll_setup
  - drivers/clk/ti/apll.c:of_omap2_apll_setup
  - drivers/clk/ti/apll.c:of_dra7_apll_setup
  - drivers/clk/ti/apll.c:of_dra7_apll_setup
  - drivers/clk/ti/interface.c:_of_ti_interface_clk_setup
```
**Symbols:**

```
c0915a40-c0915b34: ti_clk_get_reg_addr (STB_GLOBAL)
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
