# Function: <code>chained_irq_exit</code>

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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8142208e)
Location: include/linux/irqchip/chained_irq.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
```
In drivers/gpio/gpio-zx.c (ffffffff8142c0ff)
Location: include/linux/irqchip/chained_irq.h:43
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146a7da)
Location: include/linux/irqchip/chained_irq.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
```
In drivers/gpio/gpio-zx.c (ffffffff81477194)
Location: include/linux/irqchip/chained_irq.h:43
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8148996a)
Location: include/linux/irqchip/chained_irq.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148e884)
Location: include/linux/irqchip/chained_irq.h:43
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814982a0)
Location: include/linux/irqchip/chained_irq.h:43
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d4500)
Location: include/linux/irqchip/chained_irq.h:43
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81505520)
Location: include/linux/irqchip/chained_irq.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:43
Inline: True
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8151a070)
Location: include/linux/irqchip/chained_irq.h:43
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:43
Inline: True
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815481f0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81569110)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160b80b)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162feea)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167be8f)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81613b92)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165ed4f)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81682cf5)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d18ff)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179ed89)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa9cf)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b5a02)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819271bf)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f8ab2)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196b38f)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81940442)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4e6f)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/irqchip/irq-al-fic.c (ffff80001066a920)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff80001066b1dc)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff80001066b468)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_handle_irq
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c2a8)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
```
```
In drivers/irqchip/irq-partition-percpu.c (ffff800010675a94)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff8000106770a4)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_irq_handle
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff80001067771c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff800010679fb8)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_handle_cascade_irq
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067a99c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_handle_cascade_irq
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b14c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_irq_handler
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067babc)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_handle_irq
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d580)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e4c4)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069ae38)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069dc3c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff80001069fc80)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a0b60)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3824)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handler
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a4f90)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_irq_handler
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000106ac268)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_irq_handler
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106adb94)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b58c4)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_handler
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7a00)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce3e8)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:gpio_irq_handler
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ceb10)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d1918)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d27d4)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3928)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f35c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010724268)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_msi_handler_low
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_msi_handler_high
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_leg_handler
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725c44)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_isr
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff80001072692c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_handler
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010727a88)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010728178)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b4ec)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072cb88)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_isr
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072eb60)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800010732fe0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_handler
```
```
In drivers/edac/altera_edac.c (ffff800010b15f94)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/irqchip/irq-al-fic.c (c0812ff4)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
```
In drivers/irqchip/exynos-combiner.c (c08139c4)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c0814558)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_handler
```
```
In drivers/irqchip/irq-gic.c (c0814bb8)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
```
```
In drivers/irqchip/irq-partition-percpu.c (c081dee0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081e7d8)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_handle_cascade_irq
```
```
In drivers/irqchip/irq-aspeed-i2c-ic.c (c0821d08)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_irq_handler
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c082309c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_handler
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c08389e4)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
```
```
In drivers/pinctrl/pinctrl-single.c (c083f3f0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0844878)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0845c94)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_handler
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084de44)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084ee78)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852274)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_demux_eint16_31
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_eint0_15
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_eint0_15
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c08586c4)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_handler
```
```
In drivers/gpio/gpio-ftgpio010.c (c0868684)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
```
```
In drivers/gpio/gpio-mvebu.c (c086b0c8)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_irq_handler
```
```
In drivers/gpio/gpio-mxc.c (c086bebc)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx2_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
  - drivers/gpio/gpio-mxc.c:mx3_gpio_irq_handler
```
```
In drivers/gpio/gpio-pl061.c (c086ee18)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_handler
```
```
In drivers/gpio/gpio-tegra.c (c0871d4c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_handler
```
```
In drivers/gpio/gpio-vf610.c (c087361c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_handler
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a7df0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
```
```
In drivers/pci/controller/pcie-altera.c (c08b2208)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_isr
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b2d1c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_isr
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b4cc8)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intr_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b803c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_chained_msi_isr
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf5c0)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/irqchip/irq-al-fic.c (c0000000008208c0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833f70)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c000000000838474)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/gpio/gpio-ftgpio010.c (c000000000849e2c)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
```
```
In drivers/pci/controller/pci-ftpci100.c (c000000000890ef4)
Location: include/linux/irqchip/chained_irq.h:32
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
In drivers/irqchip/irq-al-fic.c (ffffffe0004954dc)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_irq_handler
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a146a)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a38fc)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae722)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_irq_handler
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e5db6)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8e78)
Location: include/linux/irqchip/chained_irq.h:32
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
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154f720)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155d440)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
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
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81577360)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/irqchip/chained_irq.h:32
Inline: True
```
</details>
</li>
</ul>

## Differences
