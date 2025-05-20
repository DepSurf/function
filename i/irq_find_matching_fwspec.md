# Function: <code>irq_find_matching_fwspec</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e5b40)
Location: kernel/irq/irqdomain.c:245
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff810e5b40-ffffffff810e5bff: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec4c0)
Location: kernel/irq/irqdomain.c:243
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff810ec4c0-ffffffff810ec57f: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ebdf0)
Location: kernel/irq/irqdomain.c:379
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff810ebdf0-ffffffff810ebea2: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f42d0)
Location: kernel/irq/irqdomain.c:380
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff810f42d0-ffffffff810f4388: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fc6b0)
Location: kernel/irq/irqdomain.c:382
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff810fc6b0-ffffffff810fc775: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107f60)
Location: kernel/irq/irqdomain.c:382
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff81107f60-ffffffff81108025: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811115a0)
Location: kernel/irq/irqdomain.c:382
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff811115a0-ffffffff81111669: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111d800)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff8111d800-ffffffff8111d8c9: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811299e0)
Location: kernel/irq/irqdomain.c:369
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff811299e0-ffffffff81129aa9: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125290)
Location: kernel/irq/irqdomain.c:390
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/hpet.c:hpet_create_irq_domain
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff81125290-ffffffff81125359: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811255f0)
Location: kernel/irq/irqdomain.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff811255f0-ffffffff811256b9: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81145d20)
Location: kernel/irq/irqdomain.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff81145d20-ffffffff81145de9: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81169f20)
Location: kernel/irq/irqdomain.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff81169f20-ffffffff81169ff1: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119e970)
Location: kernel/irq/irqdomain.c:426
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff8119e970-ffffffff8119ea41: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b08f0)
Location: kernel/irq/irqdomain.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff811b08f0-ffffffff811b09c1: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c0670)
Location: kernel/irq/irqdomain.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff811c0670-ffffffff811c0741: irq_find_matching_fwspec (STB_GLOBAL)
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
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010182c68)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init_one
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init_one
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_init
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
  - drivers/irqchip/irq-mvebu-gicp.c:irq_find_host
  - drivers/irqchip/irq-mvebu-gicp.c:irq_find_host
  - drivers/irqchip/irq-mvebu-odmi.c:irq_find_host
  - drivers/irqchip/irq-mvebu-odmi.c:irq_find_host
  - drivers/irqchip/irq-sni-exiu.c:irq_find_host
  - drivers/irqchip/irq-sni-exiu.c:irq_find_host
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
  - drivers/irqchip/qcom-pdc.c:irq_find_host
  - drivers/irqchip/qcom-pdc.c:irq_find_host
  - drivers/irqchip/irq-ti-sci-intr.c:irq_find_host
  - drivers/irqchip/irq-ti-sci-intr.c:irq_find_host
  - drivers/irqchip/irq-ti-sci-inta.c:irq_find_host
  - drivers/irqchip/irq-ti-sci-inta.c:irq_find_host
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
  - drivers/acpi/irq.c:acpi_irq_create_hierarchy
  - drivers/acpi/irq.c:acpi_unregister_gsi
  - drivers/acpi/irq.c:acpi_gsi_to_irq
  - drivers/acpi/arm64/iort.c:iort_add_platform_device
  - drivers/acpi/arm64/iort.c:acpi_configure_pmsi_domain
  - drivers/acpi/arm64/iort.c:iort_get_device_domain
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
ffff800010182c68-ffff800010182d78: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d1fcc)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - arch/arm/mach-exynos/suspend.c:irq_find_host
  - arch/arm/mach-exynos/suspend.c:irq_find_host
  - arch/arm/mach-imx/gpc.c:irq_find_host
  - arch/arm/mach-imx/gpc.c:irq_find_host
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host
  - arch/arm/mach-omap2/omap-wakeupgen.c:irq_find_host
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/irqchip/irq-alpine-msi.c:irq_find_host
  - drivers/irqchip/irq-alpine-msi.c:irq_find_host
  - drivers/irqchip/irq-tegra.c:irq_find_host
  - drivers/irqchip/irq-tegra.c:irq_find_host
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_init
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_init
  - drivers/irqchip/irq-renesas-rza1.c:irq_find_host
  - drivers/irqchip/irq-renesas-rza1.c:irq_find_host
  - drivers/irqchip/irq-crossbar.c:irq_find_host
  - drivers/irqchip/irq-crossbar.c:irq_find_host
  - drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host
  - drivers/irqchip/irq-vf610-mscm-ir.c:irq_find_host
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-sysirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
  - drivers/irqchip/irq-mtk-cirq.c:irq_find_host
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
  - drivers/irqchip/irq-imx-gpcv2.c:irq_find_host
  - drivers/irqchip/irq-uniphier-aidet.c:irq_find_host
  - drivers/irqchip/irq-uniphier-aidet.c:irq_find_host
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
  - drivers/irqchip/irq-meson-gpio.c:irq_find_host
  - drivers/irqchip/qcom-pdc.c:irq_find_host
  - drivers/irqchip/qcom-pdc.c:irq_find_host
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
  - drivers/soc/tegra/pmc.c:irq_find_host
  - drivers/soc/tegra/pmc.c:irq_find_host
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
c03d1fcc-c03d20f4: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001dd630)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
c0000000001dd630-c0000000001dd7f8: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a13e)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/of.c:pci_host_bridge_of_msi_domain
  - drivers/pci/of.c:irq_find_host
  - drivers/pci/of.c:irq_find_host
  - drivers/of/irq.c:of_msi_map_get_device_domain
  - drivers/of/irq.c:irq_find_host
  - drivers/of/irq.c:irq_find_host
```
**Symbols:**

```
ffffffe00011a13e-ffffffe00011a214: irq_find_matching_fwspec (STB_GLOBAL)
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
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115de0)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff81115de0-ffffffff81115ea9: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106ad0)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff81106ad0-ffffffff81106b99: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113cd0)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff81113cd0-ffffffff81113d99: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_domain *irq_find_matching_fwspec(struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f2f0)
Location: kernel/irq/irqdomain.c:384
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/pci-acpi.c:pci_host_bridge_acpi_msi_domain
```
**Symbols:**

```
ffffffff8111f2f0-ffffffff8111f3b9: irq_find_matching_fwspec (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
