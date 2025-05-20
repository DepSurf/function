# Function: <code>irq_find_matching_host</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_find_matching_host(struct device_node *node, enum irq_domain_bus_token bus_token);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c (ffff8000114750a8)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677e38)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-cirq.c (ffff80001067848c)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff800010678a54)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678b50)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:irq_find_host
  - drivers/irqchip/irq-mvebu-gicp.c:irq_find_host
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff800010679d74)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-odmi.c:irq_find_host
  - drivers/irqchip/irq-mvebu-odmi.c:irq_find_host
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c53c)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:irq_find_host
  - drivers/irqchip/irq-sni-exiu.c:irq_find_host
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067cbdc)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067cea8)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:irq_find_host
  - drivers/irqchip/qcom-pdc.c:irq_find_host
```
```
In drivers/irqchip/irq-ti-sci-intr.c (ffff80001067df28)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-intr.c:irq_find_host
  - drivers/irqchip/irq-ti-sci-intr.c:irq_find_host
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e560)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:irq_find_host
  - drivers/irqchip/irq-ti-sci-inta.c:irq_find_host
```
```
In drivers/pci/of.c (ffff8000106f9db0)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/of/irq.c (ffff800010b753bc)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
ffff800010b74458-ffff800010b744c4: irq_find_matching_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_find_matching_host(struct device_node *node, enum irq_domain_bus_token bus_token);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-exynos/suspend.c (c032e174)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:irq_find_host
  - arch/arm/mach-exynos/suspend.c:irq_find_host
```
```
In arch/arm/mach-imx/gpc.c (c0332d4c)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - arch/arm/mach-imx/gpc.c:irq_find_host
  - arch/arm/mach-imx/gpc.c:irq_find_host
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c033c6f0)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host
```
```
In drivers/irqchip/irq-alpine-msi.c (c0813408)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:irq_find_host
  - drivers/irqchip/irq-alpine-msi.c:irq_find_host
```
```
In drivers/irqchip/irq-tegra.c (c08143e4)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-tegra.c:irq_find_host
  - drivers/irqchip/irq-tegra.c:irq_find_host
```
```
In drivers/irqchip/irq-renesas-rza1.c (c0820258)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:irq_find_host
  - drivers/irqchip/irq-renesas-rza1.c:irq_find_host
```
```
In drivers/irqchip/irq-crossbar.c (c08209d0)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:irq_find_host
  - drivers/irqchip/irq-crossbar.c:irq_find_host
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (c0820d8c)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host
  - drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c0821048)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-cirq.c (c08215d0)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c0821a14)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c0822134)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-uniphier-aidet.c:irq_find_host
  - drivers/irqchip/irq-uniphier-aidet.c:irq_find_host
```
```
In drivers/irqchip/irq-meson-gpio.c (c08226e8)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
```
```
In drivers/irqchip/qcom-pdc.c (c0822a70)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:irq_find_host
  - drivers/irqchip/qcom-pdc.c:irq_find_host
```
```
In drivers/pci/of.c (c0892430)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/soc/tegra/pmc.c (c093b634)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:irq_find_host
  - drivers/soc/tegra/pmc.c:irq_find_host
```
```
In drivers/of/irq.c (c0c57828)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
c0c56870-c0c568e4: irq_find_matching_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_find_matching_host(struct device_node *node, enum irq_domain_bus_token bus_token);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (c0000000008777c8)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/of/irq.c (c000000000c528e4)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
c000000000c51460-c000000000c514f4: irq_find_matching_host (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct irq_domain *irq_find_matching_host(struct device_node *node, enum irq_domain_bus_token bus_token);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/of.c (ffffffe0004ca03a)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/of/irq.c (ffffffe000728b6c)
Location: include/linux/irqdomain.h:307
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
ffffffe000727e18-ffffffe000727e64: irq_find_matching_host (STB_LOCAL)
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
