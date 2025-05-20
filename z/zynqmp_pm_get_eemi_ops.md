# Function: <code>zynqmp_pm_get_eemi_ops</code>

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
const struct zynqmp_eemi_ops *zynqmp_pm_get_eemi_ops();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/xilinx/zynqmp.c (ffff800010b635d8)
Location: drivers/firmware/xilinx/zynqmp.c:697
Inline: False
Direct callers:
  - drivers/clk/zynqmp/pll.c:zynqmp_pll_disable
  - drivers/clk/zynqmp/pll.c:zynqmp_pll_enable
  - drivers/clk/zynqmp/pll.c:zynqmp_pll_is_enabled
  - drivers/clk/zynqmp/pll.c:zynqmp_pll_set_rate
  - drivers/clk/zynqmp/pll.c:zynqmp_pll_set_rate
  - drivers/clk/zynqmp/pll.c:zynqmp_pll_recalc_rate
  - drivers/clk/zynqmp/pll.c:zynqmp_pll_recalc_rate
  - drivers/clk/zynqmp/clk-gate-zynqmp.c:zynqmp_clk_gate_is_enabled
  - drivers/clk/zynqmp/clk-gate-zynqmp.c:zynqmp_clk_gate_disable
  - drivers/clk/zynqmp/clk-gate-zynqmp.c:zynqmp_clk_gate_enable
  - drivers/clk/zynqmp/divider.c:zynqmp_clk_divider_set_rate
  - drivers/clk/zynqmp/divider.c:zynqmp_clk_divider_round_rate
  - drivers/clk/zynqmp/divider.c:zynqmp_clk_divider_recalc_rate
  - drivers/clk/zynqmp/clk-mux-zynqmp.c:zynqmp_clk_mux_set_parent
  - drivers/clk/zynqmp/clk-mux-zynqmp.c:zynqmp_clk_mux_get_parent
  - drivers/clk/zynqmp/clkc.c:zynqmp_clock_probe
  - drivers/soc/xilinx/zynqmp_power.c:zynqmp_pm_probe
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
  - drivers/reset/reset-zynqmp.c:zynqmp_reset_probe
  - drivers/nvmem/zynqmp_nvmem.c:zynqmp_nvmem_probe
```
**Symbols:**

```
ffff800010b635d8-ffff800010b63604: zynqmp_pm_get_eemi_ops (STB_GLOBAL)
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
