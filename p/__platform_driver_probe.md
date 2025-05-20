# Function: <code>__platform_driver_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154e010)
Location: drivers/base/platform.c:636
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff8154e010-ffffffff8154e10a: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159fde0)
Location: drivers/base/platform.c:656
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff8159fde0-ffffffff8159fee2: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815ce420)
Location: drivers/base/platform.c:670
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff815ce420-ffffffff815ce522: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e2da0)
Location: drivers/base/platform.c:670
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff815e2da0-ffffffff815e2ea2: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81649f50)
Location: drivers/base/platform.c:670
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81649f50-ffffffff8164a052: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:668
Inline: True
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81685dba-ffffffff81685ddc: __platform_driver_probe.cold.23 (STB_LOCAL)
ffffffff81685790-ffffffff81685873: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816a5a5a)
Location: drivers/base/platform.c:670
Inline: True
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff816a5a5a-ffffffff816a5a7c: __platform_driver_probe.cold.24 (STB_LOCAL)
ffffffff816a53f0-ffffffff816a54d3: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816dea46)
Location: drivers/base/platform.c:710
Inline: True
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff816dea46-ffffffff816dea68: __platform_driver_probe.cold (STB_LOCAL)
ffffffff816de380-ffffffff816de461: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff81702c34)
Location: drivers/base/platform.c:775
Inline: True
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81702c34-ffffffff81702c56: __platform_driver_probe.cold (STB_LOCAL)
ffffffff817025f0-ffffffff817026d1: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:836
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff817bceee-ffffffff817bcf10: __platform_driver_probe.cold (STB_LOCAL)
ffffffff817bbe50-ffffffff817bbf32: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:934
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81c0e4f9-ffffffff81c0e51b: __platform_driver_probe.cold (STB_LOCAL)
ffffffff817d09b0-ffffffff817d0a72: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:933
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81c008f9-ffffffff81c0091b: __platform_driver_probe.cold (STB_LOCAL)
ffffffff817b43d0-ffffffff817b4492: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:897
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81d03221-ffffffff81d03243: __platform_driver_probe.cold (STB_LOCAL)
ffffffff8183d5c0-ffffffff8183d682: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (0)
Location: drivers/base/platform.c:906
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81ecb976-ffffffff81ecb998: __platform_driver_probe.cold (STB_LOCAL)
ffffffff81980260-ffffffff8198034e: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aedc80)
Location: drivers/base/platform.c:906
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81aedc80-ffffffff81aedd90: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3c150)
Location: drivers/base/platform.c:913
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
**Symbols:**

```
ffffffff81b3c150-ffffffff81b3c203: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b93ca0)
Location: drivers/base/platform.c:913
Inline: False
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
**Symbols:**

```
ffffffff81b93ca0-ffffffff81b93d53: __platform_driver_probe (STB_GLOBAL)
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
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ee480)
Location: drivers/base/platform.c:775
Inline: False
Direct callers:
  - drivers/bus/brcmstb_gisb.c:brcm_gisb_driver_init
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_driver_init
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_driver_init
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_driver_init
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_driver_init
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_init
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_init
  - drivers/dma/mxs-dma.c:mxs_dma_module_init
  - drivers/dma/ipu/ipu_idmac.c:ipu_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-efi.c:efi_rtc_driver_init
  - drivers/rtc/rtc-mv.c:mv_rtc_driver_init
  - drivers/firmware/meson/meson_sm.c:meson_sm_driver_init
```
**Symbols:**

```
ffff8000108ee480-ffff8000108ee5e0: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09db720)
Location: drivers/base/platform.c:775
Inline: False
Direct callers:
  - drivers/bus/brcmstb_gisb.c:brcm_gisb_driver_init
  - drivers/gpio/gpio-htc-egpio.c:egpio_init
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_driver_init
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_driver_init
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_driver_init
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:vrfb_driver_init
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_init
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_init
  - drivers/dma/mxs-dma.c:mxs_dma_module_init
  - drivers/dma/ipu/ipu_idmac.c:ipu_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/asic3.c:asic3_init
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/auxdisplay/arm-charlcd.c:charlcd_driver_init
  - drivers/rtc/rtc-efi.c:efi_rtc_driver_init
  - drivers/rtc/rtc-mv.c:mv_rtc_driver_init
```
**Symbols:**

```
c09db720-c09db83c: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000985b00)
Location: drivers/base/platform.c:775
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-secvar.c:opal_secvar_init
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_driver_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-generic.c:generic_rtc_driver_init
```
**Symbols:**

```
c000000000985b00-c000000000985cd4: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe0005809f0)
Location: drivers/base/platform.c:775
Inline: False
Direct callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_driver_init
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
```
**Symbols:**

```
ffffffe0005809f0-ffffffe000580b1a: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816c8384)
Location: drivers/base/platform.c:775
Inline: True
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff816c8384-ffffffff816c83a6: __platform_driver_probe.cold (STB_LOCAL)
ffffffff816c7d40-ffffffff816c7e21: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816a3684)
Location: drivers/base/platform.c:775
Inline: True
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff816a3684-ffffffff816a36a6: __platform_driver_probe.cold (STB_LOCAL)
ffffffff816a3040-ffffffff816a3121: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff816f68f4)
Location: drivers/base/platform.c:775
Inline: True
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff816f68f4-ffffffff816f6916: __platform_driver_probe.cold (STB_LOCAL)
ffffffff816f62b0-ffffffff816f6391: __platform_driver_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __platform_driver_probe(struct platform_driver *drv, int (*probe)(struct platform_device *), struct module *module);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/platform.c (ffffffff81711194)
Location: drivers/base/platform.c:775
Inline: True
Direct callers:
  - drivers/base/platform.c:__platform_create_bundle
  - drivers/mfd/htc-i2cpld.c:htcpld_core_init
  - drivers/rtc/rtc-cmos.c:cmos_init
```
**Symbols:**

```
ffffffff81711194-ffffffff817111b6: __platform_driver_probe.cold (STB_LOCAL)
ffffffff81710b40-ffffffff81710c3c: __platform_driver_probe (STB_GLOBAL)
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
