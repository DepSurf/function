# Function: <code>chained_irq_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81421f92)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
```
In drivers/gpio/gpio-zx.c (ffffffff8142c0cb)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146a6e4)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
```
In drivers/gpio/gpio-zx.c (ffffffff81477166)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81489874)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148e7fb)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81498210)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d4470)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81505490)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:27
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81519fe0)
Location: include/linux/irqchip/chained_irq.h:27
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:27
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81548160)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81569080)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160b760)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162fe56)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167be76)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81613af6)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165ed36)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81682c56)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d18e6)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179ecd5)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa9b6)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b5945)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819271a6)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f89ed)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b376)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8194037d)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4e56)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-al-fic.c (ffff80001066a8bc)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff80001066b160)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff80001066b454)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_handle_irq
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c264)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
```
```
In drivers/irqchip/irq-partition-percpu.c (ffff800010675a04)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010676f98)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff80001067768c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff800010679f64)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067a948)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b088)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067ba0c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d470)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e424)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069ad88)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069dc28)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff80001069fbc0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a0a58)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3800)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handler
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a4ed0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106ac120)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106adad0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b5864)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce36c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:gpio_irq_handler
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ceae0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d1868)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d2730)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d38f8)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f328)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010724250)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_msi_handler_low
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_msi_handler_low
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_msi_handler_high
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_msi_handler_high
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725b68)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff800010726838)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler
```
```
In drivers/pci/controller/pcie-altera.c (ffff8000107279c8)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff8000107280d0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b4b4)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072cac0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072eb4c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800010732f5c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_handler
```
```
In drivers/edac/altera_edac.c (ffff800010b15ee4)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-al-fic.c (c0812f98)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
```
In drivers/irqchip/exynos-combiner.c (c0813974)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c08144d8)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
```
```
In drivers/irqchip/irq-gic.c (c0814b6c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
```
```
In drivers/irqchip/irq-partition-percpu.c (c081de60)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081e720)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
```
```
In drivers/irqchip/irq-aspeed-i2c-ic.c (c0821ca4)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c0822fbc)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c08388c0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
```
```
In drivers/pinctrl/pinctrl-single.c (c083f3d8)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c08447c0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0845bac)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084ddb0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084edc8)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c08521d4)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_eint0_15
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_eint0_15
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c08584b0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
```
```
In drivers/gpio/gpio-ftgpio010.c (c0868668)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
```
```
In drivers/gpio/gpio-mvebu.c (c086b00c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
```
```
In drivers/gpio/gpio-mxc.c (c086be2c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
```
```
In drivers/gpio/gpio-pl061.c (c086edf8)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
```
```
In drivers/gpio/gpio-tegra.c (c0871c84)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
```
```
In drivers/gpio/gpio-vf610.c (c08735b8)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a7db8)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
```
```
In drivers/pci/controller/pcie-altera.c (c08b2144)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b2c78)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b4c98)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b8020)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf548)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_irq_handler
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
In drivers/irqchip/irq-al-fic.c (c000000000820828)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833f58)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c00000000083837c)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/gpio/gpio-ftgpio010.c (c000000000849dec)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
```
```
In drivers/pci/controller/pci-ftpci100.c (c000000000890eb0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-al-fic.c (ffffffe000495462)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a1452)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a3836)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae700)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e5d74)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8e60)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154f690)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155d3b0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815772d0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:16
Inline: False
```
</details>
</li>
</ul>

## Differences
