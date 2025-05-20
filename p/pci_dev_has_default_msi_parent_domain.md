# Function: <code>pci_dev_has_default_msi_parent_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_dev_has_default_msi_parent_domain(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810a72d0)
Location: arch/x86/kernel/apic/msi.c:150
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
**Symbols:**

```
ffffffff810a72d0-ffffffff810a7311: pci_dev_has_default_msi_parent_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_dev_has_default_msi_parent_domain(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810aa530)
Location: arch/x86/kernel/apic/msi.c:150
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
**Symbols:**

```
ffffffff810aa530-ffffffff810aa571: pci_dev_has_default_msi_parent_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_dev_has_default_msi_parent_domain(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810b15b0)
Location: arch/x86/kernel/apic/msi.c:150
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remap_add_device
```
**Symbols:**

```
ffffffff810b15b0-ffffffff810b15f1: pci_dev_has_default_msi_parent_domain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
