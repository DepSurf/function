# Function: <code>clk_set_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e7120)
Location: drivers/clk/clk.c:1844
Inline: False
```
**Symbols:**

```
ffffffff816e7120-ffffffff816e714f: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174b4c0)
Location: drivers/clk/clk.c:1868
Inline: False
```
**Symbols:**

```
ffffffff8174b4c0-ffffffff8174b4ef: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81533d40)
Location: drivers/clk/clk.c:1868
Inline: False
```
**Symbols:**

```
ffffffff81533d40-ffffffff81533d6f: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815470f0)
Location: drivers/clk/clk.c:1870
Inline: False
```
**Symbols:**

```
ffffffff815470f0-ffffffff81547120: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815aab40)
Location: drivers/clk/clk.c:1987
Inline: False
```
**Symbols:**

```
ffffffff815aab40-ffffffff815aab70: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e2db0)
Location: drivers/clk/clk.c:2277
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff815e2db0-ffffffff815e2e3d: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fc730)
Location: drivers/clk/clk.c:2390
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff815fc730-ffffffff815fc7c0: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162f390)
Location: drivers/clk/clk.c:2530
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8162f390-ffffffff8162f420: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81650ee0)
Location: drivers/clk/clk.c:2544
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff81650ee0-ffffffff81650f70: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81701fb0)
Location: drivers/clk/clk.c:2565
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff81701fb0-ffffffff81702111: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171f2f0)
Location: drivers/clk/clk.c:2580
Inline: True
Direct callers:
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff8171f2f0-ffffffff8171f451: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ffdf0)
Location: drivers/clk/clk.c:2593
Inline: True
Direct callers:
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff816ffdf0-ffffffff816fff51: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8177a5f0)
Location: drivers/clk/clk.c:2593
Inline: True
Direct callers:
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff8177a5f0-ffffffff8177a751: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b0c80)
Location: drivers/clk/clk.c:2610
Inline: True
Direct callers:
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff818b0c80-ffffffff818b0deb: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fdd00)
Location: drivers/clk/clk.c:2800
Inline: True
Direct callers:
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff819fdd00-ffffffff819fde6b: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a45d70)
Location: drivers/clk/clk.c:2845
Inline: True
Direct callers:
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81a45d70-ffffffff81a45f56: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a91860)
Location: drivers/clk/clk.c:2845
Inline: True
Direct callers:
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81a91860-ffffffff81a91a46: clk_set_parent (STB_GLOBAL)
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
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c1620)
Location: drivers/clk/clk.c:2544
Inline: True
Direct callers:
  - drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
**Symbols:**

```
ffff8000107c1620-ffff8000107c16d0: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ededc)
Location: drivers/clk/clk.c:2544
Inline: True
Direct callers:
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init
  - drivers/clk/tegra/clk.c:tegra_init_from_table
  - drivers/clk/ti/clk-33xx.c:am33xx_dt_clk_init
  - drivers/clk/ti/clk-33xx.c:am33xx_dt_clk_init
  - drivers/clk/ti/clk-33xx.c:am33xx_dt_clk_init
  - drivers/clk/ti/clk-44xx.c:omap4xxx_dt_clk_init
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_source
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
```
**Symbols:**

```
c08ededc-c08edf7c: clk_set_parent (STB_GLOBAL)
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
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050f326)
Location: drivers/clk/clk.c:2544
Inline: True
```
**Symbols:**

```
ffffffe00050f326-ffffffe00050f3c0: clk_set_parent (STB_GLOBAL)
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
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81616f40)
Location: drivers/clk/clk.c:2544
Inline: True
```
**Symbols:**

```
ffffffff81616f40-ffffffff81616fd0: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160b470)
Location: drivers/clk/clk.c:2544
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8160b470-ffffffff8160b500: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81644d20)
Location: drivers/clk/clk.c:2544
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff81644d20-ffffffff81644db0: clk_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int clk_set_parent(struct clk *clk, struct clk *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165f240)
Location: drivers/clk/clk.c:2544
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8165f240-ffffffff8165f2d0: clk_set_parent (STB_GLOBAL)
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
