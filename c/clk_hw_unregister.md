# Function: <code>clk_hw_unregister</code>

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
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174b935)
Location: drivers/clk/clk.c:2737
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
```
**Symbols:**

```
ffffffff8174b910-ffffffff8174b924: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815341a5)
Location: drivers/clk/clk.c:2740
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
```
**Symbols:**

```
ffffffff81534180-ffffffff81534194: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815472f5)
Location: drivers/clk/clk.c:2774
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
```
**Symbols:**

```
ffffffff815472d0-ffffffff815472e4: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815ab015)
Location: drivers/clk/clk.c:2914
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
```
**Symbols:**

```
ffffffff815aaff0-ffffffff815ab004: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e2ff5)
Location: drivers/clk/clk.c:3177
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-st.c:st_clk_remove
```
**Symbols:**

```
ffffffff815e2fd0-ffffffff815e2fe4: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fc975)
Location: drivers/clk/clk.c:3478
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-st.c:st_clk_remove
```
**Symbols:**

```
ffffffff815fc950-ffffffff815fc964: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162f5d5)
Location: drivers/clk/clk.c:3821
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-st.c:st_clk_remove
```
**Symbols:**

```
ffffffff8162f5b0-ffffffff8162f5c4: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816511a5)
Location: drivers/clk/clk.c:3932
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-st.c:st_clk_remove
```
**Symbols:**

```
ffffffff81651180-ffffffff81651194: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81700995)
Location: drivers/clk/clk.c:4027
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-composite.c:clk_hw_unregister_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-st.c:st_clk_remove
```
**Symbols:**

```
ffffffff81700970-ffffffff81700984: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171deb5)
Location: drivers/clk/clk.c:4096
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
Direct callers:
  - drivers/clk/clk-divider.c:devm_clk_hw_release_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
```
**Symbols:**

```
ffffffff8171de90-ffffffff8171dea4: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fef45)
Location: drivers/clk/clk.c:4105
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
Direct callers:
  - drivers/clk/clk-divider.c:devm_clk_hw_release_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-factor.c:devm_clk_hw_register_fixed_factor_release
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:devm_clk_hw_release_mux
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
```
**Symbols:**

```
ffffffff816fef20-ffffffff816fef34: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81779745)
Location: drivers/clk/clk.c:4132
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
Direct callers:
  - drivers/clk/clk-divider.c:devm_clk_hw_release_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-factor.c:devm_clk_hw_register_fixed_factor_release
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:devm_clk_hw_release_mux
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
```
**Symbols:**

```
ffffffff81779720-ffffffff81779734: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818afad5)
Location: drivers/clk/clk.c:4205
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
Direct callers:
  - drivers/clk/clk-divider.c:devm_clk_hw_release_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-factor.c:devm_clk_hw_register_fixed_factor_release
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:devm_clk_hw_release_gate
  - drivers/clk/clk-mux.c:devm_clk_hw_release_mux
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
```
**Symbols:**

```
ffffffff818afab0-ffffffff818afaca: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fbd95)
Location: drivers/clk/clk.c:4394
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
Direct callers:
  - drivers/clk/clk-divider.c:devm_clk_hw_release_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-factor.c:devm_clk_hw_register_fixed_factor_release
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-fixed-rate.c:devm_clk_hw_register_fixed_rate_release
  - drivers/clk/clk-gate.c:devm_clk_hw_release_gate
  - drivers/clk/clk-mux.c:devm_clk_hw_release_mux
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
```
**Symbols:**

```
ffffffff819fbd60-ffffffff819fbd7a: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a44845)
Location: drivers/clk/clk.c:4453
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
Direct callers:
  - drivers/clk/clk-divider.c:devm_clk_hw_release_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-factor.c:devm_clk_hw_register_fixed_factor_release
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-fixed-rate.c:devm_clk_hw_register_fixed_rate_release
  - drivers/clk/clk-gate.c:devm_clk_hw_release_gate
  - drivers/clk/clk-mux.c:devm_clk_hw_release_mux
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
```
**Symbols:**

```
ffffffff81a44810-ffffffff81a4482a: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a90355)
Location: drivers/clk/clk.c:4499
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
Direct callers:
  - drivers/clk/clk-divider.c:devm_clk_hw_release_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-factor.c:devm_clk_hw_register_fixed_factor_release
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-fixed-rate.c:devm_clk_hw_register_fixed_rate_release
  - drivers/clk/clk-gate.c:devm_clk_hw_release_gate
  - drivers/clk/clk-mux.c:devm_clk_hw_release_mux
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-fch.c:fch_clk_remove
```
**Symbols:**

```
ffffffff81a90320-ffffffff81a9033a: clk_hw_unregister (STB_GLOBAL)
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
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c1908)
Location: drivers/clk/clk.c:3932
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove
  - drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/bcm/clk-iproc-armpll.c:iproc_armpll_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_remove
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
  - drivers/clk/sunxi-ng/ccu_common.c:sunxi_ccu_probe
```
**Symbols:**

```
ffff8000107c18c0-ffff8000107c18ec: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ee1f4)
Location: drivers/clk/clk.c:3932
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove
  - drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
```
**Symbols:**

```
c08ee1c0-c08ee1e0: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050f5e0)
Location: drivers/clk/clk.c:3932
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove
  - drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
```
**Symbols:**

```
ffffffe00050f5a0-ffffffe00050f5ca: clk_hw_unregister (STB_GLOBAL)
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
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81617205)
Location: drivers/clk/clk.c:3932
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
```
**Symbols:**

```
ffffffff816171e0-ffffffff816171f4: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160b735)
Location: drivers/clk/clk.c:3932
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-st.c:st_clk_remove
```
**Symbols:**

```
ffffffff8160b710-ffffffff8160b724: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81644fe5)
Location: drivers/clk/clk.c:3932
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-st.c:st_clk_remove
```
**Symbols:**

```
ffffffff81644fc0-ffffffff81644fd4: clk_hw_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165f505)
Location: drivers/clk/clk.c:3932
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_hw_release
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_hw_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_hw_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_hw_unregister_gate
  - drivers/clk/clk-mux.c:clk_hw_unregister_mux
  - drivers/clk/clk-fractional-divider.c:clk_hw_unregister_fractional_divider
  - drivers/clk/x86/clk-st.c:st_clk_remove
```
**Symbols:**

```
ffffffff8165f4e0-ffffffff8165f4f4: clk_hw_unregister (STB_GLOBAL)
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
