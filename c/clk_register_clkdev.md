# Function: <code>clk_register_clkdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816e40a0)
Location: drivers/clk/clkdev.c:370
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff816e40a0-ffffffff816e4142: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81748450)
Location: drivers/clk/clkdev.c:421
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff81748450-ffffffff817484bb: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81530cc0)
Location: drivers/clk/clkdev.c:421
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff81530cc0-ffffffff81530d2b: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815441b0)
Location: drivers/clk/clkdev.c:421
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff815441b0-ffffffff8154421b: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815a72c0)
Location: drivers/clk/clkdev.c:421
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff815a72c0-ffffffff815a732b: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815dee40)
Location: drivers/clk/clkdev.c:421
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff815dee40-ffffffff815deeab: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815f8770)
Location: drivers/clk/clkdev.c:418
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff815f8770-ffffffff815f87db: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162a780)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff8162a780-ffffffff8162a7e6: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c240)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff8164c240-ffffffff8164c2a6: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816fb610)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff816fb610-ffffffff816fb671: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81717f60)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff81717f60-ffffffff81717fc1: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816f9250)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff816f9250-ffffffff816f92b1: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff817739b0)
Location: drivers/clk/clkdev.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff817739b0-ffffffff81773a11: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff818a9350)
Location: drivers/clk/clkdev.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff818a9350-ffffffff818a93c7: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff819f3c40)
Location: drivers/clk/clkdev.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff819f3c40-ffffffff819f3cb7: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a3c2f0)
Location: drivers/clk/clkdev.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff81a3c2f0-ffffffff81a3c367: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a87bb0)
Location: drivers/clk/clkdev.c:313
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff81a87bb0-ffffffff81a87c27: clk_register_clkdev (STB_GLOBAL)
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
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107baf18)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
  - drivers/acpi/acpi_amba.c:acpi_amba_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-xgene.c:xgene_pmdclk_init
  - drivers/clk/clk-xgene.c:xgene_pllclk_init
  - drivers/clk/hisilicon/clk.c:hi6220_clk_register_divider
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_gate_sep
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_gate
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_divider
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_mux
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divider_clk_setup
```
**Symbols:**

```
ffff8000107baf18-ffff8000107baf98: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e6e54)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - arch/arm/mach-vexpress/spc.c:ve_spc_clk_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/hisilicon/clk.c:hi6220_clk_register_divider
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_gate_sep
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_gate
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_divider
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_mux
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_gclk_init
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_clkdiv_init
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clocks_init
  - drivers/clk/tegra/clk.c:tegra_register_devclks
  - drivers/clk/tegra/clk.c:tegra_register_devclks
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-periph.c:tegra_periph_clk_init
  - drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init
  - drivers/clk/tegra/clk-tegra-pmc.c:tegra_pmc_clk_init
  - drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc
  - drivers/clk/tegra/clk-tegra20.c:tegra20_periph_clk_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
  - drivers/clk/tegra/clk-tegra30.c:tegra30_super_clk_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre
  - drivers/clk/tegra/clk-tegra124.c:tegra124_132_clock_init_pre
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/tegra/clk-tegra124.c:tegra124_pll_init
  - drivers/clk/ti/fapll.c:ti_fapll_setup
```
**Symbols:**

```
c08e6e54-c08e6ec8: clk_register_clkdev (STB_GLOBAL)
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
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe000509e80)
Location: drivers/clk/clkdev.c:341
Inline: False
```
**Symbols:**

```
ffffffe000509e80-ffffffe000509ed0: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816122a0)
Location: drivers/clk/clkdev.c:341
Inline: False
```
**Symbols:**

```
ffffffff816122a0-ffffffff81612306: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816067f0)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff816067f0-ffffffff81606856: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81640080)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff81640080-ffffffff816400e6: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clk_register_clkdev(struct clk *clk, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a3d0)
Location: drivers/clk/clkdev.c:341
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:register_device_clock
  - drivers/acpi/acpi_apd.c:acpi_apd_setup
```
**Symbols:**

```
ffffffff8165a3d0-ffffffff8165a436: clk_register_clkdev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *dev_id</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *dev_fmt</code>
</li>
<li>
<b>Param removed. </b>
<code>void (anon)</code>
</li>
</ul>
</details>
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
