# Function: <code>irq_set_chained_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814258d1)
Location: include/linux/irq.h:537
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146f2a0)
Location: include/linux/irq.h:566
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814912ee)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
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
In drivers/gpio/gpiolib.c (ffffffff8149ad9a)
Location: include/linux/irq.h:633
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815494b5)
Location: include/linux/irq.h:664
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8155fbb5)
Location: include/linux/irq.h:665
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815904b5)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815b21e5)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165bbb8)
Location: include/linux/irq.h:726
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167b885)
Location: include/linux/irq.h:739
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/irqchip/irq-bcm2835.c (ffff8000114709b0)
Location: include/linux/irq.h:696
Inline: True
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a17c)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069cee0)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d220c)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725770)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010727c98)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072ecdc)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
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
In arch/arm/mach-omap2/prm_common.c (c033f618)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_register_chain_handler
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_cleanup
```
```
In drivers/irqchip/irq-armada-370-xp.c (c154d5f8)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
```
```
In drivers/pinctrl/pinctrl-single.c (c0840654)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
```
In drivers/gpio/gpio-mxc.c (c086c314)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b2c08)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b8194)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
```
In drivers/soc/dove/pmu.c (c158f49c)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
```
```
In drivers/mfd/asic3.c (c0a0ed84)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_irq_remove
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
In arch/powerpc/sysdev/mpic.c (c00000000135914c)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_init
```
```
In arch/powerpc/platforms/pseries/setup.c (c0000000013621ec)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/setup.c:pseries_init_irq
```
```
In drivers/pinctrl/pinctrl-single.c (c0000000008355ec)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
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
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a106e)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8fb0)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
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
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a59a5)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff81594b45)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815a5f35)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff815c0335)
Location: include/linux/irq.h:696
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
</details>
</li>
</ul>

## Differences
