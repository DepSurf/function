# Function: <code>dev_get_msi_domain</code>

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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:880
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:880
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:896
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:896
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1005
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1005
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1009
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1009
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1007
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1007
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1052
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1052
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1105
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1105
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1128
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1128
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1370
Inline: True
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
In drivers/pci/probe.c (ffffffff816214c9)
Location: include/linux/device.h:677
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi.c (ffffffff8165455f)
Location: include/linux/device.h:677
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:free_msi_irqs
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
In drivers/pci/probe.c (ffffffff81648052)
Location: include/linux/device.h:645
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi.c (ffffffff8165ee85)
Location: include/linux/device.h:645
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_dev_has_special_msi_domain
  - drivers/pci/msi.c:pci_dev_has_special_msi_domain
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:free_msi_irqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab86d)
Location: include/linux/device.h:645
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In arch/x86/pci/common.c (ffffffff81bce1c6)
Location: include/linux/device.h:645
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/pci/probe.c (ffffffff8162ac75)
Location: include/linux/device.h:651
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi.c (ffffffff81641375)
Location: include/linux/device.h:651
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_dev_has_special_msi_domain
  - drivers/pci/msi.c:pci_dev_has_special_msi_domain
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
  - drivers/pci/msi.c:free_msi_irqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e72c)
Location: include/linux/device.h:651
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In arch/x86/pci/common.c (ffffffff81bc1b86)
Location: include/linux/device.h:651
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/pci/probe.c (ffffffff8169a14a)
Location: include/linux/device.h:668
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi.c (ffffffff816b1f75)
Location: include/linux/device.h:668
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_dev_has_special_msi_domain
  - drivers/pci/msi.c:pci_dev_has_special_msi_domain
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:free_msi_irqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81815fbc)
Location: include/linux/device.h:668
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In arch/x86/pci/common.c (ffffffff81c92196)
Location: include/linux/device.h:668
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_add_device
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
In drivers/pci/probe.c (ffffffff817bb78a)
Location: include/linux/device.h:743
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi/irqdomain.c (ffffffff817d5945)
Location: include/linux/device.h:743
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_dev_has_special_msi_domain
  - drivers/pci/msi/irqdomain.c:pci_dev_has_special_msi_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81956e78)
Location: include/linux/device.h:743
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In arch/x86/pci/common.c (ffffffff81e417d6)
Location: include/linux/device.h:743
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_device_add
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
In arch/x86/kernel/apic/msi.c (ffffffff810a72d5)
Location: include/linux/device.h:740
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:pci_dev_has_default_msi_parent_domain
  - arch/x86/kernel/apic/msi.c:pci_dev_has_default_msi_parent_domain
```
```
In drivers/pci/probe.c (ffffffff818d728a)
Location: include/linux/device.h:740
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi/irqdomain.c (ffffffff818f6c55)
Location: include/linux/device.h:740
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abdd48)
Location: include/linux/device.h:740
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In arch/x86/pci/common.c (ffffffff8201be06)
Location: include/linux/device.h:740
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_device_add
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
In arch/x86/kernel/apic/msi.c (ffffffff810aa535)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:pci_dev_has_default_msi_parent_domain
  - arch/x86/kernel/apic/msi.c:pci_dev_has_default_msi_parent_domain
```
```
In kernel/irq/msi.c (ffffffff811b52a5)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_device_has_isolated_msi
```
```
In drivers/pci/probe.c (ffffffff8191a51a)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi/irqdomain.c (ffffffff8193a0b5)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a6a1)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In arch/x86/pci/common.c (ffffffff8209c4a6)
Location: include/linux/device.h:866
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_device_add
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
In arch/x86/kernel/apic/msi.c (ffffffff810b15b5)
Location: include/linux/device.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:pci_dev_has_default_msi_parent_domain
  - arch/x86/kernel/apic/msi.c:pci_dev_has_default_msi_parent_domain
```
```
In kernel/irq/msi.c (ffffffff811c5125)
Location: include/linux/device.h:898
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_device_has_isolated_msi
```
```
In drivers/pci/probe.c (ffffffff8196291a)
Location: include/linux/device.h:898
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi/irqdomain.c (ffffffff81982f15)
Location: include/linux/device.h:898
Inline: True
Inline callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_domain_supports
  - drivers/pci/msi/irqdomain.c:pci_setup_msix_device_domain
  - drivers/pci/msi/irqdomain.c:pci_setup_msi_device_domain
  - drivers/pci/msi/irqdomain.c:pci_msi_teardown_msi_irqs
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e6f1)
Location: include/linux/device.h:898
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In arch/x86/pci/common.c (ffffffff82173c86)
Location: include/linux/device.h:898
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_device_add
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
In drivers/bus/fsl-mc/fsl-mc-bus.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/bus/fsl-mc/dprc-driver.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/bus/fsl-mc/fsl-mc-msi.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/soc/ti/ti_sci_inta_msi.c (0)
Location: include/linux/device.h:1370
Inline: True
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
In drivers/pci/probe.c (c087afbc)
Location: include/linux/device.h:1370
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi.c (c089ee7c)
Location: include/linux/device.h:1370
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1370
Inline: True
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
In drivers/pci/probe.c (ffffffe0004b7396)
Location: include/linux/device.h:1370
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/pci/msi.c (ffffffe0004de01c)
Location: include/linux/device.h:1370
Inline: True
Inline callers:
  - drivers/pci/msi.c:free_msi_irqs
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1370
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1370
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1370
Inline: True
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1370
Inline: True
```
```
In drivers/pci/msi.c (0)
Location: include/linux/device.h:1370
Inline: True
```
</details>
</li>
</ul>

## Differences
