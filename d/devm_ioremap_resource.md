# Function: <code>devm_ioremap_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81403010)
Location: lib/devres.c:134
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81403010-ffffffff814030fb: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8144ac50)
Location: lib/devres.c:134
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff8144ac50-ffffffff8144ad3b: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81469610)
Location: lib/devres.c:134
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81469610-ffffffff814696fb: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8146ed00)
Location: lib/devres.c:134
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8146ed00-ffffffff8146edeb: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8149b0e0)
Location: lib/devres.c:135
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8149b0e0-ffffffff8149b1cb: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814d0370)
Location: lib/devres.c:133
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff814d0370-ffffffff814d0465: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814e4ca0)
Location: lib/devres.c:134
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff814e4ca0-ffffffff814e4d95: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:154
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815119f1-ffffffff81511a5e: devm_ioremap_resource.cold (STB_LOCAL)
ffffffff81511540-ffffffff815115d2: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8153245e-ffffffff815324cb: devm_ioremap_resource.cold (STB_LOCAL)
ffffffff81531fb0-ffffffff81532042: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81596580)
Location: lib/devres.c:173
Inline: True
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/mfd/intel_msic.c:intel_msic_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81596580-ffffffff8159658d: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815b2010)
Location: lib/devres.c:175
Inline: True
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/mfd/intel_msic.c:intel_msic_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff815b2010-ffffffff815b201d: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815bce50)
Location: lib/devres.c:197
Inline: True
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff815bce50-ffffffff815bce5d: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81624110)
Location: lib/devres.c:199
Inline: True
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81624110-ffffffff8162411d: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816f4550)
Location: lib/devres.c:199
Inline: True
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff816f4550-ffffffff816f4567: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff817e6680)
Location: lib/devres.c:185
Inline: True
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/char/tpm/tpm_crb.c:crb_map_res
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff817e6680-ffffffff817e6697: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81826670)
Location: lib/devres.c:185
Inline: True
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_add_partition
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81826670-ffffffff81826687: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81878080)
Location: lib/devres.c:185
Inline: True
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_add_partition
```
**Symbols:**

```
ffffffff81878080-ffffffff81878097: devm_ioremap_resource (STB_GLOBAL)
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
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffff80001063dfd0)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - lib/devres.c:devm_of_iomap
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/imx-weim.c:weim_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/phy/phy-xgene.c:xgene_phy_probe
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/actions/owl-common.c:owl_clk_regmap_init
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
  - drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe
  - drivers/clk/hisilicon/reset.c:hisi_reset_init
  - drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_top_probe
  - drivers/clk/mediatek/clk-mt6797.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_mcu_probe
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_top_probe
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_mcu_probe
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_top_probe
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
  - drivers/clk/socfpga/clk-s10.c:s10_clkmgr_init
  - drivers/clk/sunxi/clk-mod0.c:sun4i_a10_mod0_clk_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_clk_probe
  - drivers/clk/sunxi/clk-sun6i-apb0.c:sun6i_a31_apb0_clk_probe
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
  - drivers/clk/sunxi/clk-sun6i-ar100.c:sun6i_a31_ar100_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun50i-h6.c:sun50i_h6_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-a83t.c:sun8i_a83t_ccu_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_probe
  - drivers/reset/reset-meson.c:meson_reset_probe
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_probe
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/power/reset/msm-poweroff.c:msm_restart_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/edac/altera_edac.c:altr_edac_a10_device_add
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
```
**Symbols:**

```
ffff80001063dfd0-ffff80001063e0d0: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (c07e3ca0)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - lib/devres.c:devm_of_iomap
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/imx-weim.c:weim_probe
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_probe
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_probe
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_map_resource
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_get_soc_data
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_get_soc_data
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:vrfb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/clk-milbeaut.c:m10v_clk_probe
  - drivers/clk/actions/owl-common.c:owl_clk_regmap_init
  - drivers/clk/hisilicon/reset.c:hisi_reset_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/samsung/exynos-pmu.c:exynos_pmu_probe
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_fuse_probe
  - drivers/soc/tegra/flowctrl.c:tegra_flowctrl_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/reset/reset-meson.c:meson_reset_probe
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_probe
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/mtd/nand/raw/omap2.c:omap_nand_probe
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
  - drivers/usb/musb/musb_core.c:musb_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/reset/brcm-kona-reset.c:kona_reset_probe
  - drivers/power/reset/msm-poweroff.c:msm_restart_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/edac/armada_xp_edac.c:aurora_l2_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/clocksource/em_sti.c:em_sti_probe
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
**Symbols:**

```
c07e3ca0-c07e3d9c: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (c0000000007e7750)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - lib/devres.c:devm_of_iomap
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c0000000007e7750-c0000000007e78b0: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffe00046b58e)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - lib/devres.c:devm_of_iomap
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffe00046b58e-ffffffe00046b65e: devm_ioremap_resource (STB_GLOBAL)
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
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff8152aa3e-ffffffff8152aaab: devm_ioremap_resource.cold (STB_LOCAL)
ffffffff8152a590-ffffffff8152a622: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
**Symbols:**

```
ffffffff8151ad1e-ffffffff8151ad8b: devm_ioremap_resource.cold (STB_LOCAL)
ffffffff8151a870-ffffffff8151a902: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81526ace-ffffffff81526b3b: devm_ioremap_resource.cold (STB_LOCAL)
ffffffff81526620-ffffffff815266b2: devm_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *devm_ioremap_resource(struct device *dev, const struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:153
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8154044e-ffffffff815404bb: devm_ioremap_resource.cold (STB_LOCAL)
ffffffff8153ffa0-ffffffff81540032: devm_ioremap_resource (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct resource *res</code> ➡️ <code>const struct resource *res</code>
</li>
</ul>
</details>
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
