# Function: <code>devm_ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81402d10)
Location: lib/devres.c:25
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff81402d10-ffffffff81402d8d: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:25
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff8144aa40-ffffffff8144aa4b: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:25
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff81469400-ffffffff8146940b: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8146ea80)
Location: lib/devres.c:25
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff8146ea80-ffffffff8146eafd: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8149ae60)
Location: lib/devres.c:26
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff8149ae60-ffffffff8149aedd: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814d01c0)
Location: lib/devres.c:63
Inline: True
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff814d01c0-ffffffff814d01cd: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff814e4af0)
Location: lib/devres.c:64
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff814e4af0-ffffffff814e4afd: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815115a9)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff815114c0-ffffffff815114cd: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81532019)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff81531f30-ffffffff81531f3d: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81596990)
Location: lib/devres.c:64
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81596990-ffffffff81596a11: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815b2420)
Location: lib/devres.c:64
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff815b2420-ffffffff815b24a1: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff815bd330)
Location: lib/devres.c:68
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff815bd330-ffffffff815bd3b1: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816246d0)
Location: lib/devres.c:68
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff816246d0-ffffffff81624758: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff816f4d90)
Location: lib/devres.c:68
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff816f4d90-ffffffff816f4e30: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff817e6ed0)
Location: lib/devres.c:69
Inline: False
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff817e6ed0-ffffffff817e6f71: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81826ed0)
Location: lib/devres.c:69
Inline: False
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff81826ed0-ffffffff81826f71: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff818788e0)
Location: lib/devres.c:69
Inline: False
Direct callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
**Symbols:**

```
ffffffff818788e0-ffffffff81878981: devm_ioremap (STB_GLOBAL)
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
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffff80001063e030)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/clk/hisilicon/clk.c:hisi_clk_alloc
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe
  - drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/soc/fsl/qbman/bman_ccsr.c:fsl_bman_probe
  - drivers/soc/fsl/qbman/qman_ccsr.c:fsl_qman_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
  - drivers/mfd/altera-sysmgr.c:sysmgr_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/net/ethernet/freescale/fman/mac.c:set_fman_mac_params
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
```
**Symbols:**

```
ffff80001063df70-ffff80001063df88: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (c07e3d0c)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/bus/ti-sysc.c:sysc_map_and_check_registers
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/clk/hisilicon/clk.c:hisi_clk_alloc
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/ti/edma.c:edma_xbar_event_map
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/mmc/host/cqhci.c:cqhci_pltfm_init
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
```
**Symbols:**

```
c07e3be8-c07e3c00: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (c0000000007e77e4)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/usb/host/ehci-hcd.c:ehci_hcd_ppc_of_probe
```
**Symbols:**

```
c0000000007e76a0-c0000000007e76b0: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffe00046b5dc)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffe00046b47c-ffffffe00046b496: devm_ioremap (STB_GLOBAL)
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
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8152a5f9)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff8152a510-ffffffff8152a51d: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff8151a8d9)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff8151a7f0-ffffffff8151a7fd: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81526689)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff815265a0-ffffffff815265ad: devm_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *devm_ioremap(struct device *dev, resource_size_t offset, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81540009)
Location: lib/devres.c:68
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
Direct callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/mfd/syscon.c:syscon_probe
```
**Symbols:**

```
ffffffff8153ff20-ffffffff8153ff2d: devm_ioremap (STB_GLOBAL)
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
