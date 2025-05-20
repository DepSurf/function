# Function: <code>pci_real_dma_dev</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_dev *pci_real_dma_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162c560)
Location: drivers/pci/pci.c:6114
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff81bb99c0-ffffffff81bb99e1: pci_real_dma_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_dev *pci_real_dma_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816522c0)
Location: drivers/pci/pci.c:6188
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff81bce2d0-ffffffff81bce2f1: pci_real_dma_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_dev *pci_real_dma_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634d70)
Location: drivers/pci/pci.c:6237
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff81bc1c90-ffffffff81bc1cb1: pci_real_dma_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_dev *pci_real_dma_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a4e60)
Location: drivers/pci/pci.c:6427
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
```
**Symbols:**

```
ffffffff81c922a0-ffffffff81c922c1: pci_real_dma_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_dev *pci_real_dma_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c7350)
Location: drivers/pci/pci.c:6524
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel/iommu.c:domain_add_dev_info
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81e41920-ffffffff81e41947: pci_real_dma_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_dev *pci_real_dma_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e4920)
Location: drivers/pci/pci.c:6473
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8201bfa0-ffffffff8201bfc7: pci_real_dma_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_dev *pci_real_dma_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81927f60)
Location: drivers/pci/pci.c:6595
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff8209c640-ffffffff8209c667: pci_real_dma_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_dev *pci_real_dma_dev(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81970700)
Location: drivers/pci/pci.c:6739
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/pci.c:pci_devs_are_dma_aliases
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:device_block_translation
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff82173e20-ffffffff82173e47: pci_real_dma_dev (STB_GLOBAL)
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
