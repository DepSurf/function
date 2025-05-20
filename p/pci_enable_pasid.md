# Function: <code>pci_enable_pasid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81455ac0)
Location: drivers/pci/ats.c:237
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81455ac0-ffffffff81455b8b: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814a26f0)
Location: drivers/pci/ats.c:237
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff814a26f0-ffffffff814a27bb: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814c4340)
Location: drivers/pci/ats.c:237
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff814c4340-ffffffff814c440b: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814ce560)
Location: drivers/pci/ats.c:266
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff814ce560-ffffffff814ce614: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8150e7e0)
Location: drivers/pci/ats.c:266
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
```
**Symbols:**

```
ffffffff8150e7e0-ffffffff8150e894: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815436f0)
Location: drivers/pci/ats.c:268
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815436f0-ffffffff815437a4: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8155aa70)
Location: drivers/pci/ats.c:268
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8155aa70-ffffffff8155ab2d: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/ats.c (0)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158b19a-ffffffff8158b1b2: pci_enable_pasid.cold (STB_LOCAL)
ffffffff8158ac70-ffffffff8158ad2b: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ac5a0)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ac5a0-ffffffff815ac65d: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816556c0)
Location: drivers/pci/ats.c:360
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816556c0-ffffffff8165579f: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81675c60)
Location: drivers/pci/ats.c:361
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81675c60-ffffffff81675d3f: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81658190)
Location: drivers/pci/ats.c:361
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81658190-ffffffff8165826a: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816ca1c0)
Location: drivers/pci/ats.c:361
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816ca1c0-ffffffff816ca29a: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f0540)
Location: drivers/pci/ats.c:361
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff817f0540-ffffffff817f062b: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819188f0)
Location: drivers/pci/ats.c:361
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_pci_caps
```
**Symbols:**

```
ffffffff819188f0-ffffffff819189f2: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195bf10)
Location: drivers/pci/ats.c:361
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff8195bf10-ffffffff8195c012: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5530)
Location: drivers/pci/ats.c:362
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff819a5530-ffffffff819a5632: pci_enable_pasid (STB_GLOBAL)
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
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffff8000107160a8)
Location: drivers/pci/ats.c:295
Inline: False
```
**Symbols:**

```
ffff8000107160a8-ffff800010716184: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c08a0ac8)
Location: drivers/pci/ats.c:295
Inline: False
```
**Symbols:**

```
c08a0ac8-c08a0bc0: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c000000000886240)
Location: drivers/pci/ats.c:295
Inline: False
```
**Symbols:**

```
c000000000886240-c000000000886390: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffe0004df79a)
Location: drivers/pci/ats.c:295
Inline: False
```
**Symbols:**

```
ffffffe0004df79a-ffffffe0004df848: pci_enable_pasid (STB_GLOBAL)
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
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8159fd70)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8159fd70-ffffffff8159fe2d: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158ef00)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158ef00-ffffffff8158efbd: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a02f0)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815a02f0-ffffffff815a03ad: pci_enable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev *pdev, int features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ba720)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ba720-ffffffff815ba7dd: pci_enable_pasid (STB_GLOBAL)
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
