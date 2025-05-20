# Function: <code>dev_set_msi_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8142fa16)
Location: include/linux/device.h:889
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_set_bus_msi_domain
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147ce5c)
Location: include/linux/device.h:905
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149e3c4)
Location: include/linux/device.h:1014
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a829e)
Location: include/linux/device.h:1018
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e72de)
Location: include/linux/device.h:1016
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815168d5)
Location: include/linux/device.h:1061
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c315)
Location: include/linux/device.h:1114
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155acd0)
Location: include/linux/device.h:1137
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157bd60)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816214d5)
Location: include/linux/device.h:686
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
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
In drivers/pci/probe.c (ffffffff8164805e)
Location: include/linux/device.h:654
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a68b0)
Location: include/linux/device.h:654
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ab87b)
Location: include/linux/device.h:654
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b870f)
Location: include/linux/device.h:654
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
```
In arch/x86/pci/common.c (ffffffff81bce1d9)
Location: include/linux/device.h:654
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
In drivers/pci/probe.c (ffffffff8162ac81)
Location: include/linux/device.h:660
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff81789125)
Location: include/linux/device.h:660
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178e73a)
Location: include/linux/device.h:660
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b85f)
Location: include/linux/device.h:660
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
```
In arch/x86/pci/common.c (ffffffff81bc1b99)
Location: include/linux/device.h:660
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
In drivers/pci/probe.c (ffffffff8169a156)
Location: include/linux/device.h:677
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180ee91)
Location: include/linux/device.h:677
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff81815fca)
Location: include/linux/device.h:677
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8182446f)
Location: include/linux/device.h:677
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
```
In arch/x86/pci/common.c (ffffffff81c921a9)
Location: include/linux/device.h:677
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
In drivers/pci/probe.c (ffffffff817bb796)
Location: include/linux/device.h:752
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff8195104f)
Location: include/linux/device.h:752
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff81956e86)
Location: include/linux/device.h:752
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81964209)
Location: include/linux/device.h:752
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
```
In arch/x86/pci/common.c (ffffffff81e417e8)
Location: include/linux/device.h:752
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
In drivers/pci/probe.c (ffffffff818d7296)
Location: include/linux/device.h:749
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab571d)
Location: include/linux/device.h:749
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abdd56)
Location: include/linux/device.h:749
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd289)
Location: include/linux/device.h:749
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
```
In arch/x86/pci/common.c (ffffffff8201be18)
Location: include/linux/device.h:749
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
In drivers/pci/probe.c (ffffffff8191a526)
Location: include/linux/device.h:875
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b01943)
Location: include/linux/device.h:875
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0a6af)
Location: include/linux/device.h:875
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19df9)
Location: include/linux/device.h:875
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
```
In arch/x86/pci/common.c (ffffffff8209c4b8)
Location: include/linux/device.h:875
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
In drivers/pci/probe.c (ffffffff81962926)
Location: include/linux/device.h:907
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b5501f)
Location: include/linux/device.h:907
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5e6ff)
Location: include/linux/device.h:907
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6fa59)
Location: include/linux/device.h:907
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
```
In arch/x86/pci/common.c (ffffffff82173c98)
Location: include/linux/device.h:907
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
In drivers/bus/fsl-mc/fsl-mc-bus.c (ffff8000106808e0)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_device_add
```
```
In drivers/bus/fsl-mc/dprc-driver.c (ffff8000106837bc)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_probe
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_probe
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_probe
```
```
In drivers/pci/probe.c (ffff8000106df32c)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/acpi/arm64/iort.c (ffff8000114819c4)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/acpi/arm64/iort.c:iort_add_platform_device
  - drivers/acpi/arm64/iort.c:acpi_configure_pmsi_domain
```
```
In drivers/of/irq.c (ffff800010b75564)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_configure
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
In drivers/pci/probe.c (c087afc8)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/of/irq.c (c0c579c0)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_configure
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
In drivers/pci/probe.c (0)
Location: include/linux/device.h:1379
Inline: True
```
```
In drivers/of/irq.c (0)
Location: include/linux/device.h:1379
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
In drivers/pci/probe.c (ffffffe0004b739c)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
```
In drivers/of/irq.c (ffffffe000728cd6)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/of/irq.c:of_msi_configure
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81570280)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155e9e0)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156fab0)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81589f90)
Location: include/linux/device.h:1379
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_set_bus_msi_domain
```
</details>
</li>
</ul>

## Differences
