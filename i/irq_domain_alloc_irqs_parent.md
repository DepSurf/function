# Function: <code>irq_domain_alloc_irqs_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e17f0)
Location: kernel/irq/irqdomain.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff810e17f0-ffffffff810e1818: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6ac0)
Location: kernel/irq/irqdomain.c:1314
Inline: True
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff810e6ac0-ffffffff810e6ae8: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ed4b0)
Location: kernel/irq/irqdomain.c:1340
Inline: True
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff810ed4b0-ffffffff810ed4d8: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ebc20)
Location: kernel/irq/irqdomain.c:1484
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/htirq.c:htirq_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff810ebc20-ffffffff810ebc41: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4190)
Location: kernel/irq/irqdomain.c:1654
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff810f4190-ffffffff810f41b7: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fc610)
Location: kernel/irq/irqdomain.c:1538
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff810fc610-ffffffff810fc637: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107de0)
Location: kernel/irq/irqdomain.c:1538
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81107de0-ffffffff81107e07: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81111310)
Location: kernel/irq/irqdomain.c:1575
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81111310-ffffffff81111337: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111d570)
Location: kernel/irq/irqdomain.c:1578
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8111d570-ffffffff8111d597: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112ac80)
Location: kernel/irq/irqdomain.c:1580
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8112ac80-ffffffff8112acd2: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126470)
Location: kernel/irq/irqdomain.c:1702
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81126470-ffffffff811264c2: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126490)
Location: kernel/irq/irqdomain.c:1667
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81126490-ffffffff811264e2: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146e60)
Location: kernel/irq/irqdomain.c:1712
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81146e60-ffffffff81146eaf: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116b230)
Location: kernel/irq/irqdomain.c:1716
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8116b230-ffffffff8116b29e: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fe50)
Location: kernel/irq/irqdomain.c:1784
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8119fe50-ffffffff8119febe: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1d20)
Location: kernel/irq/irqdomain.c:1765
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
**Symbols:**

```
ffffffff811b1d20-ffffffff811b1d91: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1ad0)
Location: kernel/irq/irqdomain.c:1765
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
**Symbols:**

```
ffffffff811c1ad0-ffffffff811c1b41: irq_domain_alloc_irqs_parent (STB_GLOBAL)
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
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010182840)
Location: kernel/irq/irqdomain.c:1578
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_gic_domain_alloc
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_domain_alloc
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_domain_alloc
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_domain_alloc
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_alloc
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_ap_alloc
  - drivers/irqchip/irq-sni-exiu.c:exiu_domain_alloc
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_alloc
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
**Symbols:**

```
ffff800010182840-ffff8000101828a0: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d1c5c)
Location: kernel/irq/irqdomain.c:1578
Inline: False
Direct callers:
  - arch/arm/mach-exynos/suspend.c:exynos_pmu_domain_alloc
  - arch/arm/mach-imx/gpc.c:imx_gpc_domain_alloc
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_domain_alloc
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_gic_domain_alloc
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_alloc
  - drivers/irqchip/irq-crossbar.c:crossbar_domain_alloc
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_domain_alloc
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_domain_alloc
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_domain_alloc
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_domain_alloc
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/soc/tegra/pmc.c:tegra_pmc_irq_alloc
```
**Symbols:**

```
c03d1c5c-c03d1c94: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe000119dda)
Location: kernel/irq/irqdomain.c:1578
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
**Symbols:**

```
ffffffe000119dda-ffffffe000119e22: irq_domain_alloc_irqs_parent (STB_GLOBAL)
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
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81115b50)
Location: kernel/irq/irqdomain.c:1578
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81115b50-ffffffff81115b77: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81106840)
Location: kernel/irq/irqdomain.c:1578
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81106840-ffffffff81106867: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81113a40)
Location: kernel/irq/irqdomain.c:1578
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81113a40-ffffffff81113a67: irq_domain_alloc_irqs_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_domain_alloc_irqs_parent(struct irq_domain *domain, unsigned int irq_base, unsigned int nr_irqs, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f060)
Location: kernel/irq/irqdomain.c:1578
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/msi.c:msi_domain_alloc
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8111f060-ffffffff8111f087: irq_domain_alloc_irqs_parent (STB_GLOBAL)
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
