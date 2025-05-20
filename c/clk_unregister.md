# Function: <code>clk_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e7150)
Location: drivers/clk/clk.c:2654
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
```
**Symbols:**

```
ffffffff816e7150-ffffffff816e7306: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174b750)
Location: drivers/clk/clk.c:2688
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff8174b750-ffffffff8174b910: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81533fc0)
Location: drivers/clk/clk.c:2691
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81533fc0-ffffffff81534180: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81547120)
Location: drivers/clk/clk.c:2725
Inline: True
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81547120-ffffffff815472cb: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815aae40)
Location: drivers/clk/clk.c:2865
Inline: True
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff815aae40-ffffffff815aafeb: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3123
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff815e4444-ffffffff815e449d: clk_unregister.cold.58 (STB_LOCAL)
ffffffff815e2e40-ffffffff815e2fc9: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3424
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff815fe803-ffffffff815fe85c: clk_unregister.cold.61 (STB_LOCAL)
ffffffff815fc7c0-ffffffff815fc949: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3767
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81630ed8-ffffffff81630f31: clk_unregister.cold (STB_LOCAL)
ffffffff8162f420-ffffffff8162f5a7: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3875
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81652c52-ffffffff81652cad: clk_unregister.cold (STB_LOCAL)
ffffffff81650f70-ffffffff81651179: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3965
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff8170289b-ffffffff817028f4: clk_unregister.cold (STB_LOCAL)
ffffffff81700730-ffffffff81700964: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:4034
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
  - drivers/clk/clk.c:devm_clk_unregister_cb
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81c04155-ffffffff81c041ae: clk_unregister.cold (STB_LOCAL)
ffffffff8171dc50-ffffffff8171de84: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:4043
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
  - drivers/clk/clk.c:devm_clk_unregister_cb
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81bf5b61-ffffffff81bf5bba: clk_unregister.cold (STB_LOCAL)
ffffffff816fece0-ffffffff816fef14: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:4070
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
  - drivers/clk/clk.c:devm_clk_unregister_cb
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81cf31fa-ffffffff81cf3253: clk_unregister.cold (STB_LOCAL)
ffffffff817794e0-ffffffff81779714: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:4143
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
  - drivers/clk/clk.c:devm_clk_unregister_cb
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81ebb35f-ffffffff81ebb3b8: clk_unregister.cold (STB_LOCAL)
ffffffff818af860-ffffffff818afaad: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fba90)
Location: drivers/clk/clk.c:4332
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
  - drivers/clk/clk.c:devm_clk_unregister_cb
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff819fba90-ffffffff819fbd49: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a44540)
Location: drivers/clk/clk.c:4391
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
  - drivers/clk/clk.c:devm_clk_unregister_cb
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81a44540-ffffffff81a447f9: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a90050)
Location: drivers/clk/clk.c:4437
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_unregister_cb
  - drivers/clk/clk.c:devm_clk_unregister_cb
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81a90050-ffffffff81a90309: clk_unregister (STB_GLOBAL)
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
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c16d0)
Location: drivers/clk/clk.c:3875
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
  - drivers/clk/imx/clk.c:imx_unregister_clocks
  - drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll
  - drivers/clk/rockchip/clk-mmc-phase.c:rockchip_clk_register_mmc
  - drivers/clk/sunxi/clk-factors.c:sunxi_factors_unregister
  - drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup
```
**Symbols:**

```
ffff8000107c16d0-ffff8000107c18c0: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08edf7c)
Location: drivers/clk/clk.c:3875
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
  - drivers/clk/imx/clk.c:imx_unregister_clocks
  - drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll
  - drivers/clk/rockchip/clk-mmc-phase.c:rockchip_clk_register_mmc
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/ti/clk.c:ti_clk_register
  - drivers/clk/ti/composite.c:_register_composite
```
**Symbols:**

```
c08edf7c-c08ee1c0: clk_unregister (STB_GLOBAL)
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
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050f3c0)
Location: drivers/clk/clk.c:3875
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffe00050f3c0-ffffffe00050f5a0: clk_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3875
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81618cb2-ffffffff81618d0d: clk_unregister.cold (STB_LOCAL)
ffffffff81616fd0-ffffffff816171d9: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3875
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff8160d1e2-ffffffff8160d23d: clk_unregister.cold (STB_LOCAL)
ffffffff8160b500-ffffffff8160b709: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3875
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81646a92-ffffffff81646aed: clk_unregister.cold (STB_LOCAL)
ffffffff81644db0-ffffffff81644fb9: clk_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void clk_unregister(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3875
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_release
  - drivers/clk/clk.c:devm_clk_release
  - drivers/clk/clk-divider.c:clk_unregister_divider
  - drivers/clk/clk-fixed-factor.c:clk_unregister_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_unregister_fixed_rate
  - drivers/clk/clk-gate.c:clk_unregister_gate
  - drivers/clk/clk-mux.c:clk_unregister_mux
  - drivers/clk/clk-composite.c:clk_unregister_composite
```
**Symbols:**

```
ffffffff81661022-ffffffff8166107d: clk_unregister.cold (STB_LOCAL)
ffffffff8165f2d0-ffffffff8165f4d9: clk_unregister (STB_GLOBAL)
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
