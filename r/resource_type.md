# Function: <code>resource_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In lib/devres.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In drivers/pci/bus.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In drivers/pci/host-bridge.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In drivers/dma/acpi-dma.c (ffffffff814be78f)
Location: include/linux/ioport.h:169
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/ioport.h:169
Inline: True
```
```
In drivers/base/platform.c (ffffffff8154dbab)
Location: include/linux/ioport.h:169
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/linux/ioport.h:169
Inline: True
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
In kernel/resource.c (ffffffff8108a332)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff8144ac6d)
Location: include/linux/ioport.h:197
Inline: True
```
```
In drivers/pci/bus.c (ffffffff8147adbe)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8147d91a)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
```
In drivers/pci/host-bridge.c (ffffffff8147e7fd)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8147f46b)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8148c366)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/ioport.h:197
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d6c80)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff8150e48b)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8157cf11)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
```
```
In drivers/base/platform.c (ffffffff8159f9de)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core.c (ffffffff816da95f)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
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
In kernel/resource.c (ffffffff8108f282)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff8146962d)
Location: include/linux/ioport.h:197
Inline: True
```
```
In drivers/pci/bus.c (ffffffff8149c240)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8149ef02)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff8149fe9d)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff814a1f12)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814adb56)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/ioport.h:197
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff814f2961)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f92e5)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_watchdog.c (ffffffff8200c0f6)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
```
In drivers/dma/acpi-dma.c (ffffffff8153a5eb)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815a93d1)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
```
```
In drivers/base/platform.c (ffffffff815ce01e)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core.c (ffffffff8170a5fa)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
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
In kernel/resource.c (ffffffff8108c222)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff8146ed1d)
Location: include/linux/ioport.h:197
Inline: True
```
```
In drivers/pci/bus.c (ffffffff814a5ff5)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff814a8d51)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff814a9cc4)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff814abb4a)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814b7ef9)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:197
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff81500579)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815083d9)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff8154ddab)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/base/platform.c (ffffffff815e2a4a)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81720c9d)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81723fdc)
Location: include/linux/ioport.h:197
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In kernel/resource.c (ffffffff81092f62)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff8149b0fd)
Location: include/linux/ioport.h:200
Inline: True
```
```
In drivers/pci/bus.c (ffffffff814e4e30)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff814e7d81)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff814e8f24)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff814eac0a)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814f8049)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:200
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff81542770)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8154a7c9)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff815b145f)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/base/platform.c (ffffffff81649bfa)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81792010)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795443)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In kernel/resource.c (ffffffff826f35e5)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff814d0391)
Location: include/linux/ioport.h:200
Inline: True
```
```
In drivers/pci/bus.c (ffffffff81514306)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8151743d)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff815186bf)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8151c026)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81528ba6)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:200
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff815786ec)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81580ac5)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff815e988f)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8166011f)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/platform.c (ffffffff816851be)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d49c9)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d7f19)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In kernel/resource.c (ffffffff828aa3cd)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff814e4cc1)
Location: include/linux/ioport.h:200
Inline: True
```
```
In drivers/pci/bus.c (ffffffff81529a6a)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8152cebd)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff8152e13f)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8152ff16)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8153ea46)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:200
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff8159033c)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81598735)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff81603d6f)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e772)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/platform.c (ffffffff816a4e1e)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:platform_get_irq
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fbae2)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ff0ac)
Location: include/linux/ioport.h:200
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In kernel/resource.c (ffffffff828c2bb8)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff81511562)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff81558cd3)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8155d558)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff8155d8ed)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8155f247)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8156dec7)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff815c111c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815ca059)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff81636758)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b5356)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/platform.c (ffffffff816dddbf)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:platform_get_irq
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183c93e)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff828cb1c1)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff81531fd2)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff8157a265)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8157e5cc)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff8157e95d)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff81580387)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8158eea7)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff815e23dc)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815eb279)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff81658478)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d8036)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/platform.c (ffffffff81701f25)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186e33e)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff810b05ca)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:__reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff815964b4)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff8161f39a)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff81623ae0)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff81623e83)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff816258b7)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81633e61)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:211
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff8168cdd2)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
  - drivers/acpi/resource.c:acpi_dev_consumes_res
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81696d29)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff81708824)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8178c5ac)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
```
In drivers/iommu/dma-iommu.c (ffffffff81791f1b)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/base/platform.c (ffffffff817bbabd)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_wc
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8194211a)
Location: include/linux/ioport.h:211
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff810abcea)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - kernel/resource.c:__request_region
  - kernel/resource.c:__reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff815b1f44)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff81645b8a)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff81bf77ff)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff81649a43)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8164b6b7)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81658f11)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8167bb4e)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/resource.c (ffffffff816aaad2)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
  - drivers/acpi/resource.c:acpi_dev_consumes_res
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b3e79)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff81725834)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff817a2b40)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be19b)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/base/platform.c (ffffffff817d070d)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_wc
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/base/platform.c:platform_get_mem_or_io
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8194846a)
Location: include/linux/ioport.h:215
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff810acad6)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff815bcd64)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff816288cc)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff81be970d)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff8162c5fc)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8162e297)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/ioport.h:216
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8165ea1c)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/resource.c (ffffffff8168d3ee)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81696129)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff817070c4)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81785840)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1a8a)
Location: include/linux/ioport.h:216
Inline: True
```
```
In drivers/base/platform.c (ffffffff817b412d)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource_wc
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/base/platform.c:platform_get_mem_or_io
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192bdca)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff810be656)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff81624024)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff8169821c)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff81ce40b3)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff8169baec)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8169d557)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/ioport.h:216
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff816d15b9)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/resource.c (ffffffff81702c1e)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170bed9)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff81782974)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180c380)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182a471)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/base/platform.c (ffffffff8183da4d)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/base/platform.c:platform_get_mem_or_io
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cef8a)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff810d57f6)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff816f4453)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff817b94f4)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff81eaaae9)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff817bd37c)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff817bf866)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (0)
Location: include/linux/ioport.h:216
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff817fa65d)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/resource.c (ffffffff81830bd4)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8183a4d9)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff818b9404)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194ca37)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196a859)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/base/platform.c (ffffffff819806eb)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_irq_byname_optional
  - drivers/base/platform.c:platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/base/platform.c:platform_get_mem_or_io
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30d0e)
Location: include/linux/ioport.h:216
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff810f47a6)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff817e6503)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff818d4079)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff818d7ef0)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff818d944c)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff818dc61f)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff818f00e6)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8192689b)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/resource.c (ffffffff81963d64)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/dma/acpi-dma.c (ffffffff81a06ad4)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab0b6b)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad4ea9)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/base/platform.c (ffffffff81aee210)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:__platform_get_irq_byname
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/base/platform.c:platform_get_mem_or_io
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc567e)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff81100bd6)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff818264e3)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff819172b9)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8191b180)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff8191c77c)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8191f94f)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff819335c7)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/vgaarb.c (ffffffff8196181e)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_is_boot_device
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff8196aa6b)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/resource.c (ffffffff819aa204)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/pnp/quirks.c (ffffffff81a395e8)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/dma/acpi-dma.c (ffffffff81a4f964)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afca45)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23659)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/base/platform.c (ffffffff81b3c5aa)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/base/platform.c:platform_get_mem_or_io
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d30e)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff8110a506)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - kernel/resource.c:__request_region_locked
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff81877ef3)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - lib/devres.c:__devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff8195f3be)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff819635b0)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff81964bac)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff81967ac1)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8197c32b)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
```
In drivers/pci/vgaarb.c (ffffffff819ab156)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_is_boot_device
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b422b)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_iatu_setup
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/acpi/resource.c (ffffffff819f4494)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/pnp/quirks.c (ffffffff81a84e15)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_system_pci_resources
```
```
In drivers/dma/acpi-dma.c (ffffffff81a9b604)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b50055)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7a3d9)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iova_reserve_pci_windows
```
```
In drivers/base/platform.c (ffffffff81b940f6)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:devm_platform_get_irqs_affinity_release
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:devm_platform_ioremap_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
  - drivers/base/platform.c:platform_get_mem_or_io
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de31fe)
Location: include/linux/ioport.h:223
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff80001144282c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffff80001063dfec)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffff8000106dcb34)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffff8000106dfeac)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffff8000106e1268)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffff8000106e5bb0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffff8000106f41b4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/of.c (ffff8000106f9ee0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f5c8)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-aardvark.c (ffff80001072038c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff8000107221d0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-altera.c (ffff8000107274dc)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072adf4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c4c4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_host_init
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffff80001072eea0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/pci/controller/pci-xgene.c (ffff800010739a64)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_setup_ob_reg
```
```
In drivers/acpi/resource.c (ffff80001076eda8)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_amba.c (ffff800010777408)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/acpi/pci_mcfg.c (ffff80001079fcc0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/pci_mcfg.c:pci_mcfg_lookup
  - drivers/acpi/pci_mcfg.c:pci_mcfg_lookup
```
```
In drivers/dma/acpi-dma.c (ffff8000107ff01c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/xen/arm-device.c (ffff80001083c23c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/xen/arm-device.c:xen_map_device_mmio
  - drivers/xen/arm-device.c:xen_unmap_device_mmio
```
```
In drivers/tty/serial/8250/8250_of.c (ffff800010893018)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3644)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca8c4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
```
In drivers/base/platform.c (ffff8000108ed460)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab19e0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In arch/arm/kernel/bios32.c (c03115f0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
```
```
In kernel/resource.c (c151c82c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:allocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (c07e3cc4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (c0878728)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (c087bb4c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (c087cf08)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (c087ec3c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (c088ec4c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/of.c (c0892550)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a81d4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pcie-rcar.c (c08aeba0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b1104)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
```
In drivers/pci/controller/pcie-altera.c (c08b27b4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b62bc)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b836c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/tty/serial/8250/8250_of.c (c098e390)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
```
```
In drivers/base/platform.c (c09db348)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (c0b93108)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (c0000000013665a8)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (c0000000007e7788)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (c000000000854bf8)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (c000000000858b40)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (c00000000085a470)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (c00000000085ca30)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (c000000000872838)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/of.c (c000000000877994)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008911dc)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093af74)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/base/platform.c (c0000000009854fc)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (c000000000b94e9c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffe000004cfa)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffe00046b5a4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffe0004b4fa0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffe0004b7d7c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffe0004b8e96)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffe0004ba6ec)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffe0004c7336)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/of.c (ffffffe0004ca114)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/of.c:pci_parse_request_of_pci_ranges
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e63da)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e90b0)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559b24)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/base/platform.c (ffffffe0005805c8)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b97ea)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff828b3fb4)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff8152a5b2)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff8156e783)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff81572aec)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff81572e7d)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff815748a7)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81582d27)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff815d469c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/dma/acpi-dma.c (ffffffff8161e318)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169da86)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/platform.c (ffffffff816c7675)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:devm_platform_ioremap_resource
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
In kernel/resource.c (ffffffff828ac135)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff8151a892)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff8155cee5)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8156124c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff815615dd)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff81563007)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81571b07)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff815be25c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c5c99)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff81612a08)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b476)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/platform.c (ffffffff816a2975)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:devm_platform_ioremap_resource
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
In kernel/resource.c (ffffffff828c6eb3)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff81526642)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff8156dfb5)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8157231c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff815726ad)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff815740d7)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81582bf7)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff815d66bc)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815df559)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff8164c2b8)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cbcf6)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/platform.c (ffffffff816f5be5)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (ffffffff818624ce)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
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
In kernel/resource.c (ffffffff828cc1fe)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:reallocate_resource
  - kernel/resource.c:__find_resource
  - kernel/resource.c:__find_resource
```
```
In lib/devres.c (ffffffff8153ffc2)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - lib/devres.c:devm_ioremap_resource
```
```
In drivers/pci/bus.c (ffffffff81588495)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:devm_request_pci_bus_resources
```
```
In drivers/pci/probe.c (ffffffff8158c7fc)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/host-bridge.c (ffffffff8158cb8d)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_bus_to_resource
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
  - drivers/pci/host-bridge.c:pcibios_resource_to_bus
```
```
In drivers/pci/pci.c (ffffffff8158e5b7)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_cfg_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8159d0a7)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/ioport.h:209
Inline: True
```
```
In drivers/acpi/resource.c (ffffffff815f057c)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f9419)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/dma/acpi-dma.c (ffffffff81666858)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e61c6)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
```
In drivers/base/platform.c (ffffffff81710475)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/base/platform.c:platform_device_add
  - drivers/base/platform.c:platform_get_resource_byname
  - drivers/base/platform.c:__platform_get_irq
  - drivers/base/platform.c:devm_platform_ioremap_resource
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187d72e)
Location: include/linux/ioport.h:209
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_dev_irq_from_resources
```
</details>
</li>
</ul>

## Differences
