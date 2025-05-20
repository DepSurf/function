# Function: <code>pci_find_host_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81432e87)
Location: drivers/pci/host-bridge.c:19
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
**Symbols:**

```
ffffffff81432fe0-ffffffff81433000: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8147e7bb)
Location: drivers/pci/host-bridge.c:19
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
**Symbols:**

```
ffffffff8147e860-ffffffff8147e880: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8149fe5b)
Location: drivers/pci/host-bridge.c:19
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
**Symbols:**

```
ffffffff8149ff00-ffffffff8149ff20: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff814a9c9b)
Location: drivers/pci/host-bridge.c:19
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/setup-irq.c:pci_fixup_irqs
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
**Symbols:**

```
ffffffff814a9d30-ffffffff814a9d50: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff814e8efb)
Location: drivers/pci/host-bridge.c:19
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
```
**Symbols:**

```
ffffffff814e8f90-ffffffff814e8fb0: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81518685)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:shpchp_is_native
  - drivers/pci/pci-acpi.c:pciehp_is_native
```
**Symbols:**

```
ffffffff81518720-ffffffff81518740: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8152e105)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff8152e1a0-ffffffff8152e1c0: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8155d8b9)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff8155d950-ffffffff8155d96e: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8157e929)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff8157e9c0-ffffffff8157e9de: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81623e4c)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aer.c:aer_remove
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pci-acpi.c:pci_acpi_optimize_delay
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_suspend
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff81623ee0-ffffffff81623efe: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81649a0c)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pci-acpi.c:pci_acpi_optimize_delay
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_suspend
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff81649aa0-ffffffff81649abe: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8162c5cc)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:pci_aer_init
  - drivers/pci/pcie/aer.c:pci_aer_clear_fatal_status
  - drivers/pci/pcie/aer.c:pci_aer_clear_nonfatal_status
  - drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting
  - drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_suspend
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
```
**Symbols:**

```
ffffffff8162c650-ffffffff8162c66e: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8169babc)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:pcie_aer_is_native
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_suspend
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff8169b9d0-ffffffff8169b9ee: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff817bd34c)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pcie/portdrv_core.c:get_port_device_capability
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:pcie_aer_is_native
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_suspend
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff817bd200-ffffffff817bd224: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff818d941c)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:pcie_aer_is_native
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_suspend
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff818d92a0-ffffffff818d92c4: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8191c74c)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:pcie_aer_is_native
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_suspend
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff8191c5d0-ffffffff8191c5f4: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81964b7c)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_ltr
  - drivers/pci/probe.c:pci_configure_extended_tags
  - drivers/pci/probe.c:pci_alloc_child_bus
  - drivers/pci/pci.c:pcie_set_readrq
  - drivers/pci/setup-res.c:pci_resize_resource
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pcie/portdrv.c:get_port_device_capability
  - drivers/pci/pcie/aer.c:aer_root_reset
  - drivers/pci/pcie/aer.c:handles_cxl_error_iter
  - drivers/pci/pcie/aer.c:pcie_aer_is_native
  - drivers/pci/pcie/err.c:pcie_do_recovery
  - drivers/pci/pcie/dpc.c:pci_dpc_recovered
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_runtime_suspend
  - drivers/pci/hotplug/pciehp_core.c:pciehp_suspend
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/pci/p2pdma.c:calc_map_type_and_dist
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
**Symbols:**

```
ffffffff81964a00-ffffffff81964a24: pci_find_host_bridge (STB_GLOBAL)
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
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffff8000106e1234)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - arch/arm64/kernel/pci.c:pci_acpi_scan_root
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
**Symbols:**

```
ffff8000106e12e0-ffff8000106e1314: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (c087cedc)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - arch/arm/kernel/bios32.c:pcibios_align_resource
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
**Symbols:**

```
c087cf70-c087cf9c: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (c00000000085a440)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
**Symbols:**

```
c00000000085a4f0-c00000000085a518: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffe0004b8e7c)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/pciehp_core.c:pme_is_native
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
**Symbols:**

```
ffffffe0004b8eee-ffffffe0004b8f18: pci_find_host_bridge (STB_GLOBAL)
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
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81572e49)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81572ee0-ffffffff81572efe: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff815615a9)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81561640-ffffffff8156165e: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81572679)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff81572710-ffffffff8157272e: pci_find_host_bridge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pci_host_bridge *pci_find_host_bridge(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8158cb59)
Location: drivers/pci/host-bridge.c:20
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-irq.c:pci_assign_irq
  - drivers/pci/pci-acpi.c:pci_acpi_setup
  - drivers/pci/pci-acpi.c:acpi_pci_add_bus
  - drivers/pci/pci-acpi.c:pciehp_is_native
  - drivers/pci/quirks.c:quirk_no_ext_tags
  - drivers/pci/pcie/portdrv_core.c:pcie_port_device_register
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
```
**Symbols:**

```
ffffffff8158cbf0-ffffffff8158cc0e: pci_find_host_bridge (STB_GLOBAL)
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
