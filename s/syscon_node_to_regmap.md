# Function: <code>syscon_node_to_regmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff815960e0)
Location: drivers/mfd/syscon.c:95
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
```
**Symbols:**

```
ffffffff815960e0-ffffffff8159615b: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff815eaeb0)
Location: drivers/mfd/syscon.c:115
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
```
**Symbols:**

```
ffffffff815eaeb0-ffffffff815eaf2b: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81617cc0)
Location: drivers/mfd/syscon.c:117
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
```
**Symbols:**

```
ffffffff81617cc0-ffffffff81617d3b: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8162bbb0)
Location: drivers/mfd/syscon.c:117
Inline: False
```
**Symbols:**

```
ffffffff8162bbb0-ffffffff8162bc2f: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81694510)
Location: drivers/mfd/syscon.c:117
Inline: False
```
**Symbols:**

```
ffffffff81694510-ffffffff8169458f: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff816d07d0)
Location: drivers/mfd/syscon.c:138
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
```
**Symbols:**

```
ffffffff816d07d0-ffffffff816d084f: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff816f1e00)
Location: drivers/mfd/syscon.c:138
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
```
**Symbols:**

```
ffffffff816f1e00-ffffffff816f1e7f: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8172b3b0)
Location: drivers/mfd/syscon.c:153
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
```
**Symbols:**

```
ffffffff8172b3b0-ffffffff8172b42b: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8174f420)
Location: drivers/mfd/syscon.c:182
Inline: True
```
**Symbols:**

```
ffffffff8174f420-ffffffff8174f432: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8180db30)
Location: drivers/mfd/syscon.c:181
Inline: True
```
**Symbols:**

```
ffffffff8180db30-ffffffff8180db42: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8181c840)
Location: drivers/mfd/syscon.c:183
Inline: True
```
**Symbols:**

```
ffffffff8181c840-ffffffff8181c852: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff817ffc10)
Location: drivers/mfd/syscon.c:183
Inline: True
```
**Symbols:**

```
ffffffff817ffc10-ffffffff817ffc22: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8188a010)
Location: drivers/mfd/syscon.c:183
Inline: True
```
**Symbols:**

```
ffffffff8188a010-ffffffff8188a022: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff819d32d0)
Location: drivers/mfd/syscon.c:183
Inline: True
```
**Symbols:**

```
ffffffff819d32d0-ffffffff819d32e6: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81b4d700)
Location: drivers/mfd/syscon.c:182
Inline: True
```
**Symbols:**

```
ffffffff81b4d700-ffffffff81b4d716: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81ba0b70)
Location: drivers/mfd/syscon.c:197
Inline: True
```
**Symbols:**

```
ffffffff81ba0b70-ffffffff81ba0b86: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81bf4cd0)
Location: drivers/mfd/syscon.c:201
Inline: True
```
**Symbols:**

```
ffffffff81bf4cd0-ffffffff81bf4ce6: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffff80001094ec10)
Location: drivers/mfd/syscon.c:182
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_regmap_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_gates_with_dev
  - drivers/clk/mediatek/clk-cpumux.c:mtk_clk_register_cpumuxes
  - drivers/clk/mediatek/reset.c:mtk_register_reset_controller_common
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_register_muxes
  - drivers/clk/meson/meson-aoclk.c:meson_aoclkc_probe
  - drivers/clk/meson/meson-eeclk.c:meson_eeclkc_probe
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe
  - drivers/clk/mvebu/ap806-system-controller.c:ap806_syscon_common_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/rockchip/grf.c:rockchip_grf_init
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/reset/reset-berlin.c:berlin2_reset_probe
  - drivers/reset/reset-imx7.c:imx7_reset_probe
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_compatible
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
ffff80001094ec10-ffff80001094ec64: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (c0a38b18)
Location: drivers/mfd/syscon.c:182
Inline: True
Direct callers:
  - arch/arm/mach-omap2/control.c:omap_control_init
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_init
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinctrl_probe
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_regmap_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_cc_g6_of_clk_init_driver
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/mediatek/clk-mtk.c:mtk_clk_register_gates_with_dev
  - drivers/clk/mediatek/clk-cpumux.c:mtk_clk_register_cpumuxes
  - drivers/clk/mediatek/reset.c:mtk_register_reset_controller_common
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_register_muxes
  - drivers/clk/meson/meson8b.c:meson8b_clkc_init_common
  - drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_probe
  - drivers/clk/versatile/clk-icst.c:of_syscon_icst_setup
  - drivers/soc/amlogic/meson-gx-socinfo.c:meson_gx_socinfo_init
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-mx-socinfo.c:meson_mx_socinfo_init
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/rockchip/grf.c:rockchip_grf_init
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/samsung/exynos-pmu.c:exynos_get_pmu_regmap
  - drivers/reset/reset-berlin.c:berlin2_reset_probe
  - drivers/reset/reset-imx7.c:imx7_reset_probe
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_compatible
  - drivers/power/reset/arm-versatile-reboot.c:versatile_reboot_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
c0a38b18-c0a38b5c: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (c0000000009fb510)
Location: drivers/mfd/syscon.c:182
Inline: False
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_compatible
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
c0000000009fb510-c0000000009fb588: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffe0005bf8de)
Location: drivers/mfd/syscon.c:182
Inline: True
Direct callers:
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_phandle
  - drivers/mfd/syscon.c:syscon_regmap_lookup_by_compatible
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
**Symbols:**

```
ffffffe0005bf8de-ffffffe0005bf92a: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff81704390)
Location: drivers/mfd/syscon.c:182
Inline: True
```
**Symbols:**

```
ffffffff81704390-ffffffff817043a2: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff816d7e10)
Location: drivers/mfd/syscon.c:182
Inline: True
```
**Symbols:**

```
ffffffff816d7e10-ffffffff816d7e22: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff817428e0)
Location: drivers/mfd/syscon.c:182
Inline: True
```
**Symbols:**

```
ffffffff817428e0-ffffffff817428f2: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct regmap *syscon_node_to_regmap(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (ffffffff8175dd20)
Location: drivers/mfd/syscon.c:182
Inline: True
```
**Symbols:**

```
ffffffff8175dd20-ffffffff8175dd32: syscon_node_to_regmap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
