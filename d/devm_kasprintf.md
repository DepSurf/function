# Function: <code>devm_kasprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154fa80)
Location: drivers/base/devres.c:863
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff8154fa80-ffffffff8154fae5: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1860)
Location: drivers/base/devres.c:863
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff815a1860-ffffffff815a18c5: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815cff10)
Location: drivers/base/devres.c:864
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff815cff10-ffffffff815cff75: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4a70)
Location: drivers/base/devres.c:864
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff815e4a70-ffffffff815e4ad6: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164bd40)
Location: drivers/base/devres.c:864
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff8164bd40-ffffffff8164bda6: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687360)
Location: drivers/base/devres.c:868
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
```
**Symbols:**

```
ffffffff81687360-ffffffff816873c5: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a6f50)
Location: drivers/base/devres.c:898
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff816a6f50-ffffffff816a6fb5: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816e0020)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/ata/libata-core.c:ata_host_activate
  - drivers/spi/spi.c:spi_register_controller
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff816e0020-ffffffff816e0085: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704260)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/spi/spi.c:spi_register_controller
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff81704260-ffffffff817042c5: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817be690)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/misc/sram.c:sram_add_partition
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/power/supply/charger-manager.c:charger_manager_prepare_sysfs
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff817be690-ffffffff817be6f5: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d33f0)
Location: drivers/base/devres.c:1036
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/misc/sram.c:sram_add_partition
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/power/supply/charger-manager.c:charger_manager_prepare_sysfs
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff817d33f0-ffffffff817d3455: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b6e00)
Location: drivers/base/devres.c:1036
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff817b6e00-ffffffff817b6e65: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840700)
Location: drivers/base/devres.c:1025
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/misc/sram.c:sram_add_partition
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff81840700-ffffffff81840765: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81983860)
Location: drivers/base/devres.c:1025
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/misc/sram.c:sram_add_partition
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff81983860-ffffffff819838df: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af17a0)
Location: drivers/base/devres.c:1030
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/misc/sram.c:sram_add_partition
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff81af17a0-ffffffff81af181f: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b3f930)
Location: drivers/base/devres.c:1031
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/misc/sram.c:sram_add_partition
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff81b3f930-ffffffff81b3f9af: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b977b0)
Location: drivers/base/devres.c:1031
Inline: False
Direct callers:
  - lib/devres.c:__devm_ioremap_resource
  - drivers/pinctrl/core.c:pinctrl_init_device_debugfs
  - drivers/misc/sram.c:sram_add_partition
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/nvmem/core.c:nvmem_populate_sysfs_cells
```
**Symbols:**

```
ffffffff81b977b0-ffffffff81b9782f: devm_kasprintf (STB_GLOBAL)
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
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108efdf0)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_pll_divider
  - drivers/clk/mvebu/armada_ap_cp_helper.c:ap_cp_unique_name
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/spi/spi.c:spi_register_controller
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_name
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_name
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_name
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_name
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_name
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_name
```
**Symbols:**

```
ffff8000108efdf0-ffff8000108efe90: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dd630)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_map_resource
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_register
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_of
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/mtd/nand/raw/omap2.c:omap_nand_probe
  - drivers/spi/spi.c:spi_register_controller
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_dai
  - sound/soc/soc-dapm.c:snd_soc_dapm_alloc_kcontrol
```
**Symbols:**

```
c09dd630-c09dd694: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989550)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/ata/libata-core.c:ata_host_activate
  - drivers/spi/spi.c:spi_register_controller
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
c000000000989550-c000000000989598: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe0005826a6)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/spi/spi.c:spi_register_controller
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffe0005826a6-ffffffe0005826f6: devm_kasprintf (STB_GLOBAL)
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
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c99b0)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/spi/spi.c:spi_register_controller
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff816c99b0-ffffffff816c9a15: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a4ce0)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff816a4ce0-ffffffff816a4d45: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f7f20)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/spi/spi.c:spi_register_controller
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff816f7f20-ffffffff816f7f85: devm_kasprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *devm_kasprintf(struct device *dev, gfp_t gfp, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817127c0)
Location: drivers/base/devres.c:920
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/spi/spi.c:spi_register_controller
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
**Symbols:**

```
ffffffff817127c0-ffffffff81712825: devm_kasprintf (STB_GLOBAL)
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
