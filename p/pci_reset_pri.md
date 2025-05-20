# Function: <code>pci_reset_pri</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81455a20)
Location: drivers/pci/ats.c:205
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81455a20-ffffffff81455ab7: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814a2650)
Location: drivers/pci/ats.c:205
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff814a2650-ffffffff814a26e7: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814c42a0)
Location: drivers/pci/ats.c:205
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff814c42a0-ffffffff814c4337: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814ce3d0)
Location: drivers/pci/ats.c:236
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff814ce3d0-ffffffff814ce418: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8150e650)
Location: drivers/pci/ats.c:236
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
```
**Symbols:**

```
ffffffff8150e650-ffffffff8150e69a: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81543550)
Location: drivers/pci/ats.c:238
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81543550-ffffffff81543599: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8155a8d0)
Location: drivers/pci/ats.c:238
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8155a8d0-ffffffff8155a919: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/ats.c (0)
Location: drivers/pci/ats.c:265
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158b15c-ffffffff8158b174: pci_reset_pri.cold (STB_LOCAL)
ffffffff8158aa70-ffffffff8158aab6: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ac3a0)
Location: drivers/pci/ats.c:265
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ac3a0-ffffffff815ac3ea: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81655bc0)
Location: drivers/pci/ats.c:294
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81655bc0-ffffffff81655c10: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81676160)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81676160-ffffffff816761b0: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81658690)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81658690-ffffffff816586e0: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816ca6d0)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816ca6d0-ffffffff816ca720: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f0af0)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff817f0af0-ffffffff817f0b5d: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81918e30)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_pci_caps
```
**Symbols:**

```
ffffffff81918e30-ffffffff81918e9d: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195c450)
Location: drivers/pci/ats.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff8195c450-ffffffff8195c4bd: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5a70)
Location: drivers/pci/ats.c:296
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_pdev_enable_cap_pri
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff819a5a70-ffffffff819a5add: pci_reset_pri (STB_GLOBAL)
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
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffff800010715e18)
Location: drivers/pci/ats.c:265
Inline: False
```
**Symbols:**

```
ffff800010715e18-ffff800010715e84: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c08a0810)
Location: drivers/pci/ats.c:265
Inline: False
```
**Symbols:**

```
c08a0810-c08a0884: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c000000000885e90)
Location: drivers/pci/ats.c:265
Inline: False
```
**Symbols:**

```
c000000000885e90-c000000000885f30: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffe0004df59c)
Location: drivers/pci/ats.c:265
Inline: False
```
**Symbols:**

```
ffffffe0004df59c-ffffffe0004df5f8: pci_reset_pri (STB_GLOBAL)
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
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8159fb70)
Location: drivers/pci/ats.c:265
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8159fb70-ffffffff8159fbba: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158ed00)
Location: drivers/pci/ats.c:265
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158ed00-ffffffff8158ed4a: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a00f0)
Location: drivers/pci/ats.c:265
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815a00f0-ffffffff815a013a: pci_reset_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_reset_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ba520)
Location: drivers/pci/ats.c:265
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ba520-ffffffff815ba56a: pci_reset_pri (STB_GLOBAL)
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
