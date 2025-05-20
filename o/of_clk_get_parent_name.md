# Function: <code>of_clk_get_parent_name</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:24
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:24
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const char *of_clk_get_parent_name(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bed88)
Location: drivers/clk/clk.c:4659
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_parent_fill
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/clk-xgene.c:xgene_devclk_init
  - drivers/clk/clk-xgene.c:xgene_pmdclk_init
  - drivers/clk/clk-xgene.c:xgene_pllclk_init
  - drivers/clk/bcm/clk-iproc-armpll.c:iproc_armpll_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divider_clk_setup
  - drivers/clk/sunxi/clk-a10-codec.c:sun4i_codec_clk_setup
  - drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup
  - drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-sun4i-pll3.c:sun4i_a10_pll3_setup
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_register
  - drivers/clk/sunxi/clk-sun6i-apb0.c:sun6i_a31_apb0_clk_probe
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_clk_init
```
**Symbols:**

```
ffff8000107bed88-ffff8000107beef4: of_clk_get_parent_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *of_clk_get_parent_name(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08eb404)
Location: drivers/clk/clk.c:4659
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_parent_fill
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk-highbank.c:hb_clk_init
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/clk-milbeaut.c:m10v_cc_of_clk_init_driver
  - drivers/clk/clk-milbeaut.c:m10v_clk_probe
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/clk/mvebu/clk-corediv.c:mvebu_corediv_clk_init
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_gclk_init
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_clkdiv_init
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7778.c:r8a7778_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7778.c:r8a7778_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7779.c:r8a7779_cpg_clocks_init
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_register_clock
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_register_clock
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clocks_init
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init
  - drivers/clk/ti/divider.c:of_ti_divider_clk_setup
  - drivers/clk/ti/gate.c:_of_ti_gate_clk_setup
  - drivers/clk/ti/fixed-factor.c:of_ti_fixed_factor_clk_setup
  - drivers/clk/ti/apll.c:of_omap2_apll_setup
  - drivers/clk/ti/interface.c:_of_ti_interface_clk_setup
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clock_setup
  - drivers/clk/versatile/clk-icst.c:of_syscon_icst_setup
  - drivers/clk/versatile/clk-versatile.c:cm_osc_setup
```
**Symbols:**

```
c08eb404-c08eb568: of_clk_get_parent_name (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *of_clk_get_parent_name(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050e0ea)
Location: drivers/clk/clk.c:4659
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_parent_fill
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
```
**Symbols:**

```
ffffffe00050e0ea-ffffffe00050e242: of_clk_get_parent_name (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (0)
Location: include/linux/of_clk.h:21
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
