# Function: <code>__irq_set_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810de6e0)
Location: kernel/irq/chip.c:789
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff810de6e0-ffffffff810de767: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e4040)
Location: kernel/irq/chip.c:847
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff810e4040-ffffffff810e40c7: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea590)
Location: kernel/irq/chip.c:856
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff810ea590-ffffffff810ea617: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9cb0)
Location: kernel/irq/chip.c:961
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/gpio/gpiolib.c:gpiochip_remove
```
**Symbols:**

```
ffffffff810e9cb0-ffffffff810e9d37: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f2200)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
```
**Symbols:**

```
ffffffff810f2200-ffffffff810f2287: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa650)
Location: kernel/irq/chip.c:982
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff810fa650-ffffffff810fa6d7: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105e10)
Location: kernel/irq/chip.c:982
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff81105e10-ffffffff81105e97: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110f2b0)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff8110f2b0-ffffffff8110f339: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b570)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff8111b570-ffffffff8111b5f9: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811278b1)
Location: kernel/irq/chip.c:1054
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff81127730-ffffffff811277b9: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811234b1)
Location: kernel/irq/chip.c:1043
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
```
**Symbols:**

```
ffffffff81123330-ffffffff811233b9: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123811)
Location: kernel/irq/chip.c:1046
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
```
**Symbols:**

```
ffffffff81123690-ffffffff81123719: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143de1)
Location: kernel/irq/chip.c:1046
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
```
**Symbols:**

```
ffffffff81143c60-ffffffff81143ce9: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811682e9)
Location: kernel/irq/chip.c:1044
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irq_sim.c:irq_sim_domain_unmap
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
```
**Symbols:**

```
ffffffff81168140-ffffffff811681dd: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119c7d9)
Location: kernel/irq/chip.c:1046
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irq_sim.c:irq_sim_domain_unmap
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
```
**Symbols:**

```
ffffffff8119c610-ffffffff8119c6ad: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae659)
Location: kernel/irq/chip.c:1061
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irq_sim.c:irq_sim_domain_unmap
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
```
**Symbols:**

```
ffffffff811ae490-ffffffff811ae52d: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811be259)
Location: kernel/irq/chip.c:1058
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irq_sim.c:irq_sim_domain_unmap
  - kernel/irq/irq_sim.c:irq_sim_domain_map
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
```
**Symbols:**

```
ffffffff811be090-ffffffff811be12d: __irq_set_handler (STB_GLOBAL)
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f598)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_free
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_domain_free
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_hwirq_alloc
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
```
**Symbols:**

```
ffff80001017f598-ffff80001017f63c: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cf7d0)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_register_chain_handler
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_irq_cleanup
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_free
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/asic3.c:asic3_irq_remove
```
**Symbols:**

```
c03cf7d0-c03cf864: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001da000)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/platforms/pseries/setup.c:pseries_init_irq
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
**Symbols:**

```
c0000000001da000-c0000000001da0c0: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe000117a5e)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffe000117a5e-ffffffe000117ac4: __irq_set_handler (STB_GLOBAL)
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
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81113b50)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff81113b50-ffffffff81113bd9: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104860)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irq_sim.c:irq_sim_init
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff81104860-ffffffff811048e9: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81111a40)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff81111a40-ffffffff81111ac9: __irq_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __irq_set_handler(unsigned int irq, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111d000)
Location: kernel/irq/chip.c:1054
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/generic-chip.c:irq_remove_generic_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_top
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/msi.c:msi_domain_ops_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_free_msi
```
**Symbols:**

```
ffffffff8111d000-ffffffff8111d089: __irq_set_handler (STB_GLOBAL)
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
