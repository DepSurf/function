# Function: <code>irq_domain_create_hierarchy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0ef0)
Location: kernel/irq/irqdomain.c:873
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
```
**Symbols:**

```
ffffffff810e0ef0-ffffffff810e0f36: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e64c0)
Location: kernel/irq/irqdomain.c:920
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff810e64c0-ffffffff810e6506: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810eceb0)
Location: kernel/irq/irqdomain.c:946
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff810eceb0-ffffffff810ecef6: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec850)
Location: kernel/irq/irqdomain.c:1113
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff810ec850-ffffffff810ec896: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f50c0)
Location: kernel/irq/irqdomain.c:1126
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff810f50c0-ffffffff810f5106: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fd490)
Location: kernel/irq/irqdomain.c:1010
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/base/platform-msi.c:platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff810fd490-ffffffff810fd4d6: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108f40)
Location: kernel/irq/irqdomain.c:1010
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81108f40-ffffffff81108f86: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81112510)
Location: kernel/irq/irqdomain.c:1047
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81112510-ffffffff81112556: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111e7a0)
Location: kernel/irq/irqdomain.c:1049
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff8111e7a0-ffffffff8111e7e6: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81129ee0)
Location: kernel/irq/irqdomain.c:1063
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81129ee0-ffffffff81129f26: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811258a0)
Location: kernel/irq/irqdomain.c:1087
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff811258a0-ffffffff811258e6: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125b90)
Location: kernel/irq/irqdomain.c:1054
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81125b90-ffffffff81125bd6: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146330)
Location: kernel/irq/irqdomain.c:1093
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81146330-ffffffff81146376: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116a5e0)
Location: kernel/irq/irqdomain.c:1095
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff8116a5e0-ffffffff8116a638: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119f170)
Location: kernel/irq/irqdomain.c:1152
Inline: False
Direct callers:
  - kernel/irq/msi.c:__msi_create_irq_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff8119f170-ffffffff8119f1df: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1050)
Location: kernel/irq/irqdomain.c:1133
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:__msi_create_irq_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff811b1050-ffffffff811b10cf: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c0dd0)
Location: kernel/irq/irqdomain.c:1133
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/msi.c:__msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff811c0dd0-ffffffff811c0e4f: irq_domain_create_hierarchy (STB_GLOBAL)
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
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010184038)
Location: kernel/irq/irqdomain.c:1049
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-sni-exiu.c:exiu_dt_init
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/acpi/irq.c:acpi_irq_create_hierarchy
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffff800010184038-ffff8000101840c4: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d31dc)
Location: kernel/irq/irqdomain.c:1049
Inline: False
Direct callers:
  - arch/arm/mach-exynos/suspend.c:exynos_pmu_irq_init
  - arch/arm/mach-imx/gpc.c:imx_gpc_init
  - arch/arm/mach-omap2/omap-wakeupgen.c:wakeupgen_init
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/irqchip/irq-tegra.c:tegra_ictlr_init
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
  - drivers/irqchip/irq-crossbar.c:irqcrossbar_init
  - drivers/irqchip/irq-vf610-mscm-ir.c:vf610_mscm_ir_of_init
  - drivers/irqchip/irq-mtk-sysirq.c:mtk_sysirq_of_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-imx-gpcv2.c:imx_gpcv2_irqchip_init
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_of_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
c03d31dc-c03d324c: irq_domain_create_hierarchy (STB_GLOBAL)
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
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b11a)
Location: kernel/irq/irqdomain.c:1049
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffe00011b11a-ffffffe00011b190: irq_domain_create_hierarchy (STB_GLOBAL)
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
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116d80)
Location: kernel/irq/irqdomain.c:1049
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81116d80-ffffffff81116dc6: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107a70)
Location: kernel/irq/irqdomain.c:1049
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81107a70-ffffffff81107ab6: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114c70)
Location: kernel/irq/irqdomain.c:1049
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff81114c70-ffffffff81114cb6: irq_domain_create_hierarchy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_domain *irq_domain_create_hierarchy(struct irq_domain *parent, unsigned int flags, unsigned int size, struct fwnode_handle *fwnode, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811202a0)
Location: kernel/irq/irqdomain.c:1049
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_create_irq_domain
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/iommu/hyperv-iommu.c:hyperv_prepare_irq_remapping
  - drivers/base/platform-msi.c:__platform_msi_create_device_domain
```
**Symbols:**

```
ffffffff811202a0-ffffffff811202e6: irq_domain_create_hierarchy (STB_GLOBAL)
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
