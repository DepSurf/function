# Function: <code>clk_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816e3e20)
Location: drivers/clk/clkdev.c:197
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/clk/clk-devres.c:devm_clk_get
```
**Symbols:**

```
ffffffff816e3e20-ffffffff816e3e55: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81748356)
Location: drivers/clk/clkdev.c:197
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/clk/clk-devres.c:devm_clk_get
```
**Symbols:**

```
ffffffff81748150-ffffffff81748185: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81530bc6)
Location: drivers/clk/clkdev.c:197
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff815309c0-ffffffff815309f5: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815440c0)
Location: drivers/clk/clkdev.c:197
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff81543eb0-ffffffff81543ee1: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815a71d0)
Location: drivers/clk/clkdev.c:197
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
**Symbols:**

```
ffffffff815a6fc0-ffffffff815a6ff1: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815ded45)
Location: drivers/clk/clkdev.c:197
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:dev_pm_opp_get_opp_table
```
**Symbols:**

```
ffffffff815deb40-ffffffff815deb71: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815f8615)
Location: drivers/clk/clkdev.c:194
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff815f8470-ffffffff815f84a1: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162aaa5)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff8162aa70-ffffffff8162aa9d: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c575)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff8164c540-ffffffff8164c56d: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816fb4d0)
Location: drivers/clk/clkdev.c:100
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff816fb4d0-ffffffff816fb54b: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81717e20)
Location: drivers/clk/clkdev.c:100
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81717e20-ffffffff81717e9b: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816f9110)
Location: drivers/clk/clkdev.c:100
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff816f9110-ffffffff816f918b: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81773870)
Location: drivers/clk/clkdev.c:100
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff81773870-ffffffff817738eb: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff818a91d0)
Location: drivers/clk/clkdev.c:100
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff818a91d0-ffffffff818a9255: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff819f3ec8)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff819f3df0-ffffffff819f3e49: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a3c588)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff81a3c4b0-ffffffff81a3c509: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a87e48)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_add_opp_table_indexed
```
**Symbols:**

```
ffffffff81a87d70-ffffffff81a87dc9: clk_get (STB_GLOBAL)
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
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107bb278)
Location: drivers/clk/clkdev.c:100
Inline: False
Direct callers:
  - drivers/phy/phy-xgene.c:xgene_phy_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_register
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
**Symbols:**

```
ffff8000107bb278-ffff8000107bb330: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e712c)
Location: drivers/clk/clkdev.c:100
Inline: False
Direct callers:
  - arch/arm/mach-omap2/io.c:omap_sdrc_init
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - arch/arm/mach-omap2/voltage.c:omap_voltage_late_init
  - drivers/bus/ti-sysc.c:sysc_notifier_call
  - drivers/bus/ti-sysc.c:sysc_notifier_call
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/clk/ti/clk.c:omap2_clk_enable_init_clocks
  - drivers/clk/ti/clk-814x.c:dm814x_adpll_enable_init_clocks
  - drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5
  - drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/power/avs/smartreflex.c:sr_set_clk_length
  - drivers/power/avs/smartreflex.c:sr_set_clk_length
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:_opp_get_opp_table
  - drivers/cpufreq/cpufreq-dt.c:cpufreq_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_source
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe
```
**Symbols:**

```
c08e712c-c08e71b0: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/linux/clk.h:745
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/clk.h:745
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/clk.h:745
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe00050a120)
Location: drivers/clk/clkdev.c:100
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/clk/clkdev.c:clk_add_alias
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
  - drivers/opp/core.c:_opp_get_opp_table
```
**Symbols:**

```
ffffffe00050a120-ffffffe00050a1a2: clk_get (STB_GLOBAL)
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
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816125d5)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff816125a0-ffffffff816125cd: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81606b25)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81606af0-ffffffff81606b1d: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816403b5)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff81640380-ffffffff816403ad: clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_get(struct device *dev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a705)
Location: drivers/clk/clkdev.c:100
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:clk_add_alias
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get
  - drivers/clk/clk-bulk.c:__clk_bulk_get
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/opp/core.c:dev_pm_opp_set_clkname
```
**Symbols:**

```
ffffffff8165a6d0-ffffffff8165a6fd: clk_get (STB_GLOBAL)
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
