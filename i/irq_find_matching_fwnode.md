# Function: <code>irq_find_matching_fwnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwnode(struct fwnode_handle *fwnode, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0180)
Location: kernel/irq/irqdomain.c:252
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff810e0180-ffffffff810e0208: irq_find_matching_fwnode (STB_GLOBAL)
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
In drivers/pci/probe.c (ffffffff8147b185)
Location: include/linux/irqdomain.h:235
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4d39)
Location: include/linux/irqdomain.h:235
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8149c605)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff814c6bb9)
Location: include/linux/irqdomain.h:242
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a64cf)
Location: include/linux/irqdomain.h:277
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff814d0b29)
Location: include/linux/irqdomain.h:277
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e530f)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff81510d6c)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8151484f)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff81545eac)
Location: include/linux/irqdomain.h:286
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff81529fb5)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff815420ac)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8155925b)
Location: include/linux/irqdomain.h:290
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff81571bfc)
Location: include/linux/irqdomain.h:290
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8157a82b)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff8159317c)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8162014b)
Location: include/linux/irqdomain.h:298
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff8164160a)
Location: include/linux/irqdomain.h:298
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff816467cb)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff81667afa)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8162934b)
Location: include/linux/irqdomain.h:301
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff8164a00a)
Location: include/linux/irqdomain.h:301
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff81698d1f)
Location: include/linux/irqdomain.h:300
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff816bbbba)
Location: include/linux/irqdomain.h:300
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff817ba25d)
Location: include/linux/irqdomain.h:314
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff817e078a)
Location: include/linux/irqdomain.h:314
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff818d516d)
Location: include/linux/irqdomain.h:302
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff8190377a)
Location: include/linux/irqdomain.h:302
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8191821c)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff81946e1a)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8196082c)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff8199013a)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (ffff800011474c18)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init_one
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (ffff800011474e28)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init_one
```
```
In drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c (ffff8000114750ac)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init
```
```
In drivers/irqchip/irq-mtk-sysirq.c (ffff800010677e40)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-cirq.c (ffff800010678494)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
```
```
In drivers/irqchip/irq-imx-gpcv2.c (ffff800010678a5c)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678b50)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:irq_find_host
  - drivers/irqchip/irq-mvebu-gicp.c:irq_find_host
```
```
In drivers/irqchip/irq-mvebu-odmi.c (ffff800010679d7c)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-odmi.c:irq_find_host
  - drivers/irqchip/irq-mvebu-odmi.c:irq_find_host
```
```
In drivers/irqchip/irq-sni-exiu.c (ffff80001067c544)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-sni-exiu.c:irq_find_host
  - drivers/irqchip/irq-sni-exiu.c:irq_find_host
```
```
In drivers/irqchip/irq-meson-gpio.c (ffff80001067cbe4)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
```
```
In drivers/irqchip/qcom-pdc.c (ffff80001067cea8)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:irq_find_host
  - drivers/irqchip/qcom-pdc.c:irq_find_host
```
```
In drivers/irqchip/irq-ti-sci-intr.c (ffff80001067df28)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-intr.c:irq_find_host
  - drivers/irqchip/irq-ti-sci-intr.c:irq_find_host
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e560)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:irq_find_host
  - drivers/irqchip/irq-ti-sci-inta.c:irq_find_host
```
```
In drivers/pci/probe.c (0)
Location: include/linux/irqdomain.h:297
Inline: True
```
```
In drivers/pci/pci-acpi.c (ffff8000106f9264)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
```
In drivers/pci/of.c (ffff8000106f9dcc)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/acpi/irq.c (ffff80001077c1f4)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/acpi/irq.c:acpi_irq_create_hierarchy
  - drivers/acpi/irq.c:acpi_unregister_gsi
  - drivers/acpi/irq.c:acpi_gsi_to_irq
Direct callers:
  - drivers/acpi/irq.c:acpi_irq_get
```
```
In drivers/acpi/arm64/iort.c (ffff80001148199c)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/acpi/arm64/iort.c:iort_add_platform_device
  - drivers/acpi/arm64/iort.c:acpi_configure_pmsi_domain
  - drivers/acpi/arm64/iort.c:iort_get_device_domain
```
```
In drivers/of/irq.c (ffff800010b753d4)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
ffff80001077c270-ffff80001077c2d4: irq_find_matching_fwnode.constprop.0 (STB_LOCAL)
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
In arch/arm/mach-exynos/suspend.c (c032e174)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:irq_find_host
  - arch/arm/mach-exynos/suspend.c:irq_find_host
```
```
In arch/arm/mach-imx/gpc.c (c0332d4c)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - arch/arm/mach-imx/gpc.c:irq_find_host
  - arch/arm/mach-imx/gpc.c:irq_find_host
```
```
In arch/arm/mach-omap2/omap-wakeupgen.c (c033c6f0)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host
```
```
In drivers/irqchip/irq-alpine-msi.c (c0813408)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-alpine-msi.c:irq_find_host
  - drivers/irqchip/irq-alpine-msi.c:irq_find_host
```
```
In drivers/irqchip/irq-tegra.c (c08143e4)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-tegra.c:irq_find_host
  - drivers/irqchip/irq-tegra.c:irq_find_host
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (c154d148)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (c154d298)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
```
```
In drivers/irqchip/irq-renesas-rza1.c (c0820258)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:irq_find_host
  - drivers/irqchip/irq-renesas-rza1.c:irq_find_host
```
```
In drivers/irqchip/irq-crossbar.c (c08209d0)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-crossbar.c:irq_find_host
  - drivers/irqchip/irq-crossbar.c:irq_find_host
```
```
In drivers/irqchip/irq-vf610-mscm-ir.c (c0820d8c)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host
  - drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-sysirq.c (c0821048)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
```
```
In drivers/irqchip/irq-mtk-cirq.c (c08215d0)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
```
```
In drivers/irqchip/irq-imx-gpcv2.c (c0821a14)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c0822134)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-uniphier-aidet.c:irq_find_host
  - drivers/irqchip/irq-uniphier-aidet.c:irq_find_host
```
```
In drivers/irqchip/irq-meson-gpio.c (c08226e8)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
```
```
In drivers/irqchip/qcom-pdc.c (c0822a70)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/irqchip/qcom-pdc.c:irq_find_host
  - drivers/irqchip/qcom-pdc.c:irq_find_host
```
```
In drivers/pci/probe.c (0)
Location: include/linux/irqdomain.h:297
Inline: True
```
```
In drivers/pci/of.c (c0892430)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/soc/tegra/pmc.c (c093b634)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:irq_find_host
  - drivers/soc/tegra/pmc.c:irq_find_host
```
```
In drivers/of/irq.c (c0c57828)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
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
In drivers/pci/of.c (c0000000008777d4)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/of/irq.c (c000000000c528f0)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
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
In drivers/pci/probe.c (0)
Location: include/linux/irqdomain.h:297
Inline: True
```
```
In drivers/pci/of.c (ffffffe0004ca03e)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
```
```
In drivers/of/irq.c (ffffffe000728b70)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156ed4b)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff8158700c)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8155d4ab)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff81575dbc)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff8156e57b)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff81586ecc)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
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
In drivers/pci/probe.c (ffffffff81588a5b)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/pci-acpi.c (ffffffff815a137c)
Location: include/linux/irqdomain.h:297
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
