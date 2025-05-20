# Function: <code>irq_find_host</code>

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
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
struct irq_domain *irq_find_host(struct device_node *node);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677e14)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
```
```
In drivers/irqchip/irq-mtk-cirq.c (ffff800010678468)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff800010678a30)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678b28)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff800010679d50)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c518)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-sni-exiu.c:exiu_dt_init
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067cbb8)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067ce80)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
```
```
In drivers/irqchip/irq-ti-sci-intr.c (ffff80001067df00)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e538)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
```
```
In drivers/pci/of.c (ffff8000106f92b8)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
```
```
In drivers/of/irq.c (ffff800010b744c8)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/of/irq.c:of_irq_get
```
**Symbols:**

```
ffff800010677e14-ffff800010677eb0: irq_find_host (STB_LOCAL)
ffff800010678468-ffff800010678504: irq_find_host (STB_LOCAL)
ffff800010678a30-ffff800010678acc: irq_find_host (STB_LOCAL)
ffff800010678b28-ffff800010678bc4: irq_find_host (STB_LOCAL)
ffff800010679d50-ffff800010679dec: irq_find_host (STB_LOCAL)
ffff80001067c518-ffff80001067c5b4: irq_find_host (STB_LOCAL)
ffff80001067cbb8-ffff80001067cc54: irq_find_host (STB_LOCAL)
ffff80001067ce80-ffff80001067cf1c: irq_find_host (STB_LOCAL)
ffff80001067df00-ffff80001067df9c: irq_find_host (STB_LOCAL)
ffff80001067e538-ffff80001067e5d4: irq_find_host (STB_LOCAL)
ffff8000106f92b8-ffff8000106f9354: irq_find_host (STB_LOCAL)
ffff800010b744c8-ffff800010b74568: irq_find_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
struct irq_domain *irq_find_host(struct device_node *node);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mach-exynos/suspend.c (c032e13c)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - arch/arm/mach-exynos/suspend.c:exynos_pmu_irq_init
```
```
In arch/arm/mach-imx/gpc.c (c0332d14)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - arch/arm/mach-imx/gpc.c:imx_gpc_init
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c033c6b8)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
```
```
In drivers/irqchip/irq-alpine-msi.c (c08133d0)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_init
```
```
In drivers/irqchip/irq-tegra.c (c08143ac)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_init
```
```
In drivers/irqchip/irq-renesas-rza1.c (c0820220)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
```
```
In drivers/irqchip/irq-crossbar.c (c0820998)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-crossbar.c:irqcrossbar_init
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (c0820d54)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c0821010)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
```
```
In drivers/irqchip/irq-mtk-cirq.c (c0821598)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c08219dc)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c08220fc)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
```
```
In drivers/irqchip/irq-meson-gpio.c (c08226b0)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init
```
```
In drivers/irqchip/qcom-pdc.c (c0822a38)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
```
```
In drivers/pci/of.c (c08918d0)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
```
```
In drivers/soc/tegra/pmc.c (c093b5fc)
Location: include/linux/irqdomain.h:313
Inline: False
```
```
In drivers/of/irq.c (c0c568e4)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/of/irq.c:of_irq_get
```
**Symbols:**

```
c032e13c-c032e1dc: irq_find_host (STB_LOCAL)
c0332d14-c0332db4: irq_find_host (STB_LOCAL)
c033c6b8-c033c758: irq_find_host (STB_LOCAL)
c08133d0-c0813474: irq_find_host (STB_LOCAL)
c08143ac-c081444c: irq_find_host (STB_LOCAL)
c0820220-c08202c4: irq_find_host (STB_LOCAL)
c0820998-c0820a38: irq_find_host (STB_LOCAL)
c0820d54-c0820df4: irq_find_host (STB_LOCAL)
c0821010-c08210b0: irq_find_host (STB_LOCAL)
c0821598-c0821638: irq_find_host (STB_LOCAL)
c08219dc-c0821a7c: irq_find_host (STB_LOCAL)
c08220fc-c08221a0: irq_find_host (STB_LOCAL)
c08226b0-c0822750: irq_find_host (STB_LOCAL)
c0822a38-c0822adc: irq_find_host (STB_LOCAL)
c08918d0-c0891974: irq_find_host (STB_LOCAL)
c093b5fc-c093b6a0: irq_find_host (STB_LOCAL)
c0c568e4-c0c56988: irq_find_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
struct irq_domain *irq_find_host(struct device_node *node);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c000000000876920)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
```
```
In drivers/of/irq.c (c000000000c51500)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/of/irq.c:of_irq_get
```
**Symbols:**

```
c000000000876920-c0000000008769e4: irq_find_host (STB_LOCAL)
c000000000c51500-c000000000c515c4: irq_find_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate ⚠️</summary>

```c
struct irq_domain *irq_find_host(struct device_node *node);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffffffe0004c9790)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
```
```
In drivers/of/irq.c (ffffffe000727e64)
Location: include/linux/irqdomain.h:313
Inline: False
Direct callers:
  - drivers/of/irq.c:of_irq_get
```
**Symbols:**

```
ffffffe000727e64-ffffffe000727ef8: irq_find_host (STB_LOCAL)
ffffffe0004c9790-ffffffe0004c9824: irq_find_host (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
