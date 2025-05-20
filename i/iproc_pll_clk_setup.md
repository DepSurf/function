# Function: <code>iproc_pll_clk_setup</code>

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
void iproc_pll_clk_setup(struct device_node *node, const struct iproc_pll_ctrl *pll_ctrl, const struct iproc_pll_vco_param *vco, unsigned int num_vco_entries, const struct iproc_clk_ctrl *clk_ctrl, unsigned int num_clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/bcm/clk-iproc-pll.c (ffff8000107cc668)
Location: drivers/clk/bcm/clk-iproc-pll.c:725
Inline: False
Direct callers:
  - drivers/clk/bcm/clk-ns2.c:ns2_lcpll_ports_clk_init
  - drivers/clk/bcm/clk-ns2.c:ns2_lcpll_ddr_clk_init
  - drivers/clk/bcm/clk-ns2.c:ns2_genpll_sw_clk_init
  - drivers/clk/bcm/clk-ns2.c:ns2_genpll_scr_clk_init
  - drivers/clk/bcm/clk-sr.c:sr_lcpll_pcie_clk_init
  - drivers/clk/bcm/clk-sr.c:sr_lcpll1_clk_init
  - drivers/clk/bcm/clk-sr.c:sr_lcpll0_clk_init
  - drivers/clk/bcm/clk-sr.c:sr_genpll5_clk_init
  - drivers/clk/bcm/clk-sr.c:sr_genpll4_clk_init
  - drivers/clk/bcm/clk-sr.c:sr_genpll3_clk_init
  - drivers/clk/bcm/clk-sr.c:sr_genpll2_clk_init
  - drivers/clk/bcm/clk-sr.c:sr_genpll0_clk_init
```
**Symbols:**

```
ffff8000107cc668-ffff8000107cca24: iproc_pll_clk_setup (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
