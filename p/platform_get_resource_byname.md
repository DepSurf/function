# Function: <code>platform_get_resource_byname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8154d8b0)
Location: drivers/base/platform.c:126
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff8154d8b0-ffffffff8154d94b: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8159f6f0)
Location: drivers/base/platform.c:146
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_host_init
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff8159f6f0-ffffffff8159f772: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815cdd30)
Location: drivers/base/platform.c:161
Inline: False
Direct callers:
  - drivers/pci/host/pcie-designware.c:dw_pcie_host_init
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff815cdd30-ffffffff815cddb2: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff815e2760)
Location: drivers/base/platform.c:161
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff815e2760-ffffffff815e27e2: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81649910)
Location: drivers/base/platform.c:161
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff81649910-ffffffff81649992: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81684ed0)
Location: drivers/base/platform.c:160
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff81684ed0-ffffffff81684f52: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a4b20)
Location: drivers/base/platform.c:161
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff816a4b20-ffffffff816a4ba2: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816ddaf0)
Location: drivers/base/platform.c:199
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff816ddaf0-ffffffff816ddb73: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81701bf0)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff81701bf0-ffffffff81701c75: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc785)
Location: drivers/base/platform.c:284
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffff817bb7e0-ffffffff817bb865: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1485)
Location: drivers/base/platform.c:436
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff817d04a0-ffffffff817d0525: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4eb5)
Location: drivers/base/platform.c:435
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff817b3ec0-ffffffff817b3f45: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e3a5)
Location: drivers/base/platform.c:415
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff8183d3a0-ffffffff8183d425: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff819811e5)
Location: drivers/base/platform.c:419
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_iatu_detect
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81980010-ffffffff819800a6: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aef48e)
Location: drivers/base/platform.c:419
Inline: True
Inline callers:
  - drivers/base/platform.c:__platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81aed9c0-ffffffff81aeda56: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3d144)
Location: drivers/base/platform.c:419
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81b3bd80-ffffffff81b3be16: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b94c84)
Location: drivers/base/platform.c:420
Inline: True
Inline callers:
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_get_resources
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffff81b938d0-ffffffff81b93966: platform_get_resource_byname (STB_GLOBAL)
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
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ed018)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/base/platform.c:__platform_get_irq_byname
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_remove
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_release_attrib
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable_device
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
```
**Symbols:**

```
ffff8000108ed018-ffff8000108ed0c8: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dafbc)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/bus/ti-sysc.c:sysc_map_and_check_registers
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/base/platform.c:__platform_get_irq_byname
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/mmc/host/cqhci.c:cqhci_pltfm_init
```
**Symbols:**

```
c09dafbc-c09db04c: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000984f60)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
**Symbols:**

```
c000000000984f60-c0000000009851e8: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe0005802da)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
**Symbols:**

```
ffffffe0005802da-ffffffe000580364: platform_get_resource_byname (STB_GLOBAL)
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
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c7340)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff816c7340-ffffffff816c73c5: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a2640)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff816a2640-ffffffff816a26c5: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f58b0)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff816f58b0-ffffffff816f5935: platform_get_resource_byname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct resource *platform_get_resource_byname(struct platform_device *dev, unsigned int type, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81710140)
Location: drivers/base/platform.c:226
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
```
**Symbols:**

```
ffffffff81710140-ffffffff817101c5: platform_get_resource_byname (STB_GLOBAL)
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
