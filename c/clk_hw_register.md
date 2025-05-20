# Function: <code>clk_hw_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174d0f6)
Location: drivers/clk/clk.c:2626
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff8174d0a0-ffffffff8174d0bf: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81535966)
Location: drivers/clk/clk.c:2629
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81535910-ffffffff8153592f: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81548d28)
Location: drivers/clk/clk.c:2663
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81548cd0-ffffffff81548cee: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815ac288)
Location: drivers/clk/clk.c:2803
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff815ac230-ffffffff815ac24e: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e41e1)
Location: drivers/clk/clk.c:3061
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff815e4180-ffffffff815e419e: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fe5d1)
Location: drivers/clk/clk.c:3362
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff815fe570-ffffffff815fe58e: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162fde1)
Location: drivers/clk/clk.c:3693
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff8162fcc0-ffffffff8162fce3: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81652391)
Location: drivers/clk/clk.c:3772
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81652270-ffffffff81652293: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81701311)
Location: drivers/clk/clk.c:3862
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff817011f0-ffffffff81701213: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171e831)
Location: drivers/clk/clk.c:3931
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff8171e710-ffffffff8171e733: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ff871)
Location: drivers/clk/clk.c:3940
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
```
**Symbols:**

```
ffffffff816ff760-ffffffff816ff780: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8177a038)
Location: drivers/clk/clk.c:3967
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
```
**Symbols:**

```
ffffffff81779fd0-ffffffff81779ff0: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b0488)
Location: drivers/clk/clk.c:4040
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
```
**Symbols:**

```
ffffffff818b0410-ffffffff818b043a: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fc978)
Location: drivers/clk/clk.c:4229
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
```
**Symbols:**

```
ffffffff819fc8f0-ffffffff819fc91a: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a453ea)
Location: drivers/clk/clk.c:4281
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81a45360-ffffffff81a4538a: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a90eda)
Location: drivers/clk/clk.c:4327
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81a90e50-ffffffff81a90e7a: clk_hw_register (STB_GLOBAL)
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
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c2e58)
Location: drivers/clk/clk.c:3772
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:__clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-armpll.c:iproc_armpll_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_register
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_register
  - drivers/clk/berlin/berlin2-pll.c:berlin2_pll_register
  - drivers/clk/imx/clk-busy.c:imx_clk_hw_busy_mux
  - drivers/clk/imx/clk-busy.c:imx_clk_hw_busy_divider
  - drivers/clk/imx/clk-cpu.c:imx_clk_hw_cpu
  - drivers/clk/imx/clk-divider-gate.c:imx_clk_divider_gate
  - drivers/clk/imx/clk-fixup-div.c:imx_clk_hw_fixup_divider
  - drivers/clk/imx/clk-fixup-mux.c:imx_clk_hw_fixup_mux
  - drivers/clk/imx/clk-frac-pll.c:imx_clk_frac_pll
  - drivers/clk/imx/clk-gate-exclusive.c:imx_clk_hw_gate_exclusive
  - drivers/clk/imx/clk-gate2.c:clk_hw_register_gate2
  - drivers/clk/imx/clk-pfd.c:imx_clk_hw_pfd
  - drivers/clk/imx/clk-pfdv2.c:imx_clk_pfdv2
  - drivers/clk/imx/clk-pllv3.c:imx_clk_hw_pllv3
  - drivers/clk/imx/clk-pllv4.c:imx_clk_pllv4
  - drivers/clk/imx/clk-sccg-pll.c:imx_clk_sccg_pll
  - drivers/clk/imx/clk-scu.c:__imx_clk_scu
  - drivers/clk/imx/clk-lpcg-scu.c:imx_clk_lpcg_scu
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/zynqmp/pll.c:zynqmp_clk_register_pll
  - drivers/clk/zynqmp/clk-gate-zynqmp.c:zynqmp_clk_register_gate
  - drivers/clk/zynqmp/divider.c:zynqmp_clk_register_divider
  - drivers/clk/zynqmp/clk-mux-zynqmp.c:zynqmp_clk_register_mux
```
**Symbols:**

```
ffff8000107c2e58-ffff8000107c2ed4: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08edac8)
Location: drivers/clk/clk.c:3772
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:__clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/clk-highbank.c:hb_clk_init
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-milbeaut.c:m10v_cc_of_clk_init_driver
  - drivers/clk/clk-milbeaut.c:m10v_clk_probe
  - drivers/clk/clk-milbeaut.c:m10v_clk_probe
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_channel_register
  - drivers/clk/berlin/berlin2-avpll.c:berlin2_avpll_vco_register
  - drivers/clk/berlin/berlin2-pll.c:berlin2_pll_register
  - drivers/clk/imx/clk-busy.c:imx_clk_hw_busy_mux
  - drivers/clk/imx/clk-busy.c:imx_clk_hw_busy_divider
  - drivers/clk/imx/clk-cpu.c:imx_clk_hw_cpu
  - drivers/clk/imx/clk-divider-gate.c:imx_clk_divider_gate
  - drivers/clk/imx/clk-fixup-div.c:imx_clk_hw_fixup_divider
  - drivers/clk/imx/clk-fixup-mux.c:imx_clk_hw_fixup_mux
  - drivers/clk/imx/clk-frac-pll.c:imx_clk_frac_pll
  - drivers/clk/imx/clk-gate-exclusive.c:imx_clk_hw_gate_exclusive
  - drivers/clk/imx/clk-gate2.c:clk_hw_register_gate2
  - drivers/clk/imx/clk-pfd.c:imx_clk_hw_pfd
  - drivers/clk/imx/clk-pfdv2.c:imx_clk_pfdv2
  - drivers/clk/imx/clk-pllv3.c:imx_clk_hw_pllv3
  - drivers/clk/imx/clk-pllv4.c:imx_clk_pllv4
  - drivers/clk/imx/clk-sccg-pll.c:imx_clk_sccg_pll
  - drivers/clk/meson/meson8b.c:meson8b_clkc_init_common
  - drivers/clk/samsung/clk-pll.c:samsung_clk_register_pll
  - drivers/clk/samsung/clk-cpu.c:exynos_register_cpu_clock
```
**Symbols:**

```
c08edac8-c08edb1c: clk_hw_register (STB_GLOBAL)
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
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe000510836)
Location: drivers/clk/clk.c:3772
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:__clk_hw_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
```
**Symbols:**

```
ffffffe000510836-ffffffe0005108ac: clk_hw_register (STB_GLOBAL)
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
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816183f1)
Location: drivers/clk/clk.c:3772
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff816182d0-ffffffff816182f3: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160c921)
Location: drivers/clk/clk.c:3772
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff8160c800-ffffffff8160c823: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816461d1)
Location: drivers/clk/clk.c:3772
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff816460b0-ffffffff816460d3: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81660761)
Location: drivers/clk/clk.c:3772
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_register
Direct callers:
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-rate.c:clk_hw_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_hw_register_gate
  - drivers/clk/clk-mux.c:clk_hw_register_mux_table
  - drivers/clk/clk-composite.c:clk_hw_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff81660640-ffffffff81660663: clk_hw_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
