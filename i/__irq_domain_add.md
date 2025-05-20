# Function: <code>__irq_domain_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0b10)
Location: kernel/irq/irqdomain.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
```
**Symbols:**

```
ffffffff810e0b10-ffffffff810e0c34: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6390)
Location: kernel/irq/irqdomain.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
```
**Symbols:**

```
ffffffff810e6390-ffffffff810e64b1: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecd80)
Location: kernel/irq/irqdomain.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810ecd80-ffffffff810ecea1: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec620)
Location: kernel/irq/irqdomain.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/htirq.c:arch_init_htirq_domain
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810ec620-ffffffff810ec842: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4e70)
Location: kernel/irq/irqdomain.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810f4e70-ffffffff810f50b5: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810fe4e7-ffffffff810fe4f8: __irq_domain_add.cold.27 (STB_LOCAL)
ffffffff810fd250-ffffffff810fd48f: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81109cb7-ffffffff81109cc8: __irq_domain_add.cold.26 (STB_LOCAL)
ffffffff81108cf0-ffffffff81108f32: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8111337c-ffffffff8111338d: __irq_domain_add.cold (STB_LOCAL)
ffffffff811122d0-ffffffff8111250b: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8111f52a-ffffffff8111f53b: __irq_domain_add.cold (STB_LOCAL)
ffffffff8111e560-ffffffff8111e79f: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8112ba2a-ffffffff8112ba3b: __irq_domain_add.cold (STB_LOCAL)
ffffffff81129cb0-ffffffff81129ed1: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81be1bd0-ffffffff81be1be1: __irq_domain_add.cold (STB_LOCAL)
ffffffff81125670-ffffffff81125891: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81bd3c48-ffffffff81bd3c59: __irq_domain_add.cold (STB_LOCAL)
ffffffff81125940-ffffffff81125b8a: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81cadc79-ffffffff81cadc8a: __irq_domain_add.cold (STB_LOCAL)
ffffffff811460d0-ffffffff8114632d: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:139
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/iommu/amd/iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81e5e168-ffffffff81e5e179: __irq_domain_add.cold (STB_LOCAL)
ffffffff8116a380-ffffffff8116a5d5: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fdde)
Location: kernel/irq/irqdomain.c:248
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8119f120-ffffffff8119f15a: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1aee)
Location: kernel/irq/irqdomain.c:255
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff811b1000-ffffffff811b103a: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c189e)
Location: kernel/irq/irqdomain.c:255
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_allocate_domains
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff811c0d80-ffffffff811c0dba: __irq_domain_add (STB_GLOBAL)
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
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183cd8)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_allocate_domains
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
```
**Symbols:**

```
ffff800010183cd8-ffff800010184034: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d2f50)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_init
  - drivers/irqchip/exynos-combiner.c:combiner_init
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-partition-percpu.c:partition_create_desc
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-rda-intc.c:rda8810_intc_init
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_of_init
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_host_init
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
**Symbols:**

```
c03d2f50-c03d31dc: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001de320)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/xics/xics-common.c:xics_init
  - arch/powerpc/sysdev/xive/common.c:xive_core_init
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c0000000001de320-c0000000001de6f0: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011aede)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
  - drivers/irqchip/irq-sifive-plic.c:plic_init
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffe00011aede-ffffffe00011b11a: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
**Symbols:**

```
ffffffff81117b0a-ffffffff81117b1b: __irq_domain_add.cold (STB_LOCAL)
ffffffff81116b40-ffffffff81116d7f: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
**Symbols:**

```
ffffffff811087fa-ffffffff8110880b: __irq_domain_add.cold (STB_LOCAL)
ffffffff81107830-ffffffff81107a6f: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff811159fa-ffffffff81115a0b: __irq_domain_add.cold (STB_LOCAL)
ffffffff81114a30-ffffffff81114c6f: __irq_domain_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct irq_domain *__irq_domain_add(struct fwnode_handle *fwnode, int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:arch_early_irq_init
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/iommu/amd_iommu.c:amd_iommu_create_irq_domain
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/max8997-irq.c:max8997_irq_init
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8112102a-ffffffff8112103b: __irq_domain_add.cold (STB_LOCAL)
ffffffff81120060-ffffffff8112029f: __irq_domain_add (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
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
