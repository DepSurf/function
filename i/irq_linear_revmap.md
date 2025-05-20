# Function: <code>irq_linear_revmap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In drivers/irqchip/irq-bcm2835.c (ffff80001066ac50)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2835.c:bcm2836_chained_handle_irq
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff800010677704)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069adf0)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff80001069fc20)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3740)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_handle_bank
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf134)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_cascade
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800010732f98)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_legacy_irq_handler
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_msi_irq_handler
```
```
In drivers/edac/altera_edac.c (ffff800010b15f50)
Location: include/linux/irqdomain.h:400
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
In drivers/irqchip/irq-armada-370-xp.c (c081e4d4)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_resume
  - drivers/irqchip/irq-armada-370-xp.c:armada_xp_mpic_reenable_percpu
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083892c)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_demux
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0844820)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084de10)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852334)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_eint0_15
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_irq
```
```
In drivers/gpio/gpio-mpc8xxx.c (c0869824)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_cascade
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf58c)
Location: include/linux/irqdomain.h:400
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
In arch/powerpc/sysdev/mpic.c (c0000000000b5808)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0000000008383f8)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a3892)
Location: include/linux/irqdomain.h:400
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_irq_handler
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
