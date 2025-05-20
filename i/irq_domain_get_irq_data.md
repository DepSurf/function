# Function: <code>irq_domain_get_irq_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0330)
Location: kernel/irq/irqdomain.c:1006
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_find_mapping
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff810e0330-ffffffff810e0367: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6310)
Location: kernel/irq/irqdomain.c:1054
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff810e5cf0-ffffffff810e5d23: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecd00)
Location: kernel/irq/irqdomain.c:1080
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff810ec6e0-ffffffff810ec713: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec100)
Location: kernel/irq/irqdomain.c:1249
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff810ec010-ffffffff810ec043: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f498e)
Location: kernel/irq/irqdomain.c:1249
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff810f44f0-ffffffff810f4523: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fcd7e)
Location: kernel/irq/irqdomain.c:1133
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff810fc900-ffffffff810fc933: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8110862e)
Location: kernel/irq/irqdomain.c:1133
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff811081b0-ffffffff811081e3: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81111c30)
Location: kernel/irq/irqdomain.c:1170
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff811117f0-ffffffff8111181d: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111de9f)
Location: kernel/irq/irqdomain.c:1172
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8111da60-ffffffff8111da8d: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a914)
Location: kernel/irq/irqdomain.c:1186
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81129b80-ffffffff81129bb0: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126524)
Location: kernel/irq/irqdomain.c:1292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81125430-ffffffff81125460: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126544)
Location: kernel/irq/irqdomain.c:1259
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
```
**Symbols:**

```
ffffffff81125790-ffffffff811257c0: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146d04)
Location: kernel/irq/irqdomain.c:1299
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
```
**Symbols:**

```
ffffffff81145eb0-ffffffff81145ee0: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116b0f4)
Location: kernel/irq/irqdomain.c:1301
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_domain_unmap
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8116a0e0-ffffffff8116a118: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119ff24)
Location: kernel/irq/irqdomain.c:1361
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_domain_unmap
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8119eb60-ffffffff8119eb98: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1dfe)
Location: kernel/irq/irqdomain.c:1340
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_domain_unmap
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
**Symbols:**

```
ffffffff811b0a50-ffffffff811b0a88: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1bae)
Location: kernel/irq/irqdomain.c:1340
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_info
  - kernel/irq/irqdomain.c:irq_domain_disconnect_hierarchy
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_free
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_free
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/irq_sim.c:irq_sim_domain_unmap
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd/iommu.c:irq_remapping_free
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_alloc
```
**Symbols:**

```
ffffffff811c07d0-ffffffff811c0808: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101834fc)
Location: kernel/irq/irqdomain.c:1172
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_free
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_free
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_free
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-mvebu-gicp.c:gicp_irq_domain_free
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_free
  - drivers/irqchip/irq-mvebu-odmi.c:odmi_irq_domain_alloc
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_cp_domain_free
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_domain_free
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_domain_irq_free
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_free
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_free
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_free
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_free
  - drivers/pci/controller/pci-aardvark.c:advk_msi_irq_domain_free
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_irq_domain_free
  - drivers/pci/controller/pci-xgene-msi.c:xgene_irq_domain_free
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_irq_domain_free
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_free
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_irq_msi_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
```
**Symbols:**

```
ffff800010182f90-ffff800010182fdc: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d27d8)
Location: kernel/irq/irqdomain.c:1172
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_free
  - drivers/irqchip/irq-alpine-msi.c:alpine_msix_middle_domain_alloc
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_free
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_free
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_free
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_msi_free
  - drivers/irqchip/irq-crossbar.c:crossbar_domain_free
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_free
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_free
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_free
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
```
**Symbols:**

```
c03d2320-c03d2364: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001de2cc)
Location: kernel/irq/irqdomain.c:1702
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
**Symbols:**

```
c0000000001dda90-c0000000001ddaf0: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a876)
Location: kernel/irq/irqdomain.c:1172
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
```
**Symbols:**

```
ffffffe00011a40c-ffffffe00011a44a: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111647f)
Location: kernel/irq/irqdomain.c:1172
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81116040-ffffffff8111606d: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8110716f)
Location: kernel/irq/irqdomain.c:1172
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81106d30-ffffffff81106d5d: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111436f)
Location: kernel/irq/irqdomain.c:1172
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81113f30-ffffffff81113f5d: irq_domain_get_irq_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct irq_data *irq_domain_get_irq_data(struct irq_domain *domain, unsigned int virq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f99f)
Location: kernel/irq/irqdomain.c:1172
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_pop_irq
  - kernel/irq/irqdomain.c:irq_domain_free_irqs_common
  - kernel/irq/irqdomain.c:irq_domain_set_hwirq_and_chip
  - kernel/irq/irqdomain.c:irq_find_mapping
Direct callers:
  - arch/x86/kernel/apic/vector.c:irq_force_complete_move
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
  - arch/x86/kernel/apic/vector.c:x86_vector_free_irqs
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - kernel/irq/generic-chip.c:irq_unmap_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_alloc_irqs
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_free
  - drivers/iommu/amd_iommu.c:irq_remapping_free
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8111f550-ffffffff8111f57d: irq_domain_get_irq_data (STB_GLOBAL)
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
