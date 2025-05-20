# Function: <code>pci_ats_supported</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_ats_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816554b5)
Location: drivers/pci/ats.c:40
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81655450-ffffffff81655477: pci_ats_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pci_ats_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81675a55)
Location: drivers/pci/ats.c:40
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816759f0-ffffffff81675a17: pci_ats_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_ats_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81657f85)
Location: drivers/pci/ats.c:40
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81657f20-ffffffff81657f47: pci_ats_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_ats_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816c9fb5)
Location: drivers/pci/ats.c:40
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff816c9f50-ffffffff816c9f77: pci_ats_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool pci_ats_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f02c5)
Location: drivers/pci/ats.c:40
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
**Symbols:**

```
ffffffff817f0260-ffffffff817f028d: pci_ats_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool pci_ats_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81918505)
Location: drivers/pci/ats.c:40
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
**Symbols:**

```
ffffffff81918480-ffffffff819184ad: pci_ats_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool pci_ats_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195bb25)
Location: drivers/pci/ats.c:40
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_info
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
**Symbols:**

```
ffffffff8195baa0-ffffffff8195bacd: pci_ats_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_ats_supported(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5145)
Location: drivers/pci/ats.c:41
Inline: True
Inline callers:
  - drivers/pci/ats.c:pci_enable_ats
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
```
**Symbols:**

```
ffffffff819a50c0-ffffffff819a50ed: pci_ats_supported (STB_GLOBAL)
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
