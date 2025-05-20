# Function: <code>pci_disable_pasid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814558e0)
Location: drivers/pci/ats.c:271
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814558e0-ffffffff8145590f: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814a2510)
Location: drivers/pci/ats.c:271
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814a2510-ffffffff814a253f: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814c4160)
Location: drivers/pci/ats.c:271
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814c4160-ffffffff814c418f: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814ce420)
Location: drivers/pci/ats.c:300
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814ce420-ffffffff814ce45e: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8150e6a0)
Location: drivers/pci/ats.c:300
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8150e6a0-ffffffff8150e6e0: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815435a0)
Location: drivers/pci/ats.c:302
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815435a0-ffffffff815435e2: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8155a920)
Location: drivers/pci/ats.c:305
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8155a920-ffffffff8155a962: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/ats.c (0)
Location: drivers/pci/ats.c:332
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8158b174-ffffffff8158b187: pci_disable_pasid.cold (STB_LOCAL)
ffffffff8158aac0-ffffffff8158ab02: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ac3f0)
Location: drivers/pci/ats.c:332
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815ac3f0-ffffffff815ac431: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81655550)
Location: drivers/pci/ats.c:406
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81655550-ffffffff81655598: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81675af0)
Location: drivers/pci/ats.c:407
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81675af0-ffffffff81675b38: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81658020)
Location: drivers/pci/ats.c:407
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81658020-ffffffff81658068: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816ca050)
Location: drivers/pci/ats.c:407
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816ca050-ffffffff816ca098: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f0370)
Location: drivers/pci/ats.c:407
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff817f0370-ffffffff817f03e8: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819185c0)
Location: drivers/pci/ats.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_disable_pci_caps
```
**Symbols:**

```
ffffffff819185c0-ffffffff81918638: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195bbe0)
Location: drivers/pci/ats.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_disable_pci_caps
```
**Symbols:**

```
ffffffff8195bbe0-ffffffff8195bc58: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5200)
Location: drivers/pci/ats.c:411
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:iommu_disable_pci_caps
```
**Symbols:**

```
ffffffff819a5200-ffffffff819a5278: pci_disable_pasid (STB_GLOBAL)
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
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffff800010715e88)
Location: drivers/pci/ats.c:332
Inline: False
```
**Symbols:**

```
ffff800010715e88-ffff800010715efc: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c08a0884)
Location: drivers/pci/ats.c:332
Inline: False
```
**Symbols:**

```
c08a0884-c08a08f8: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c000000000885f30)
Location: drivers/pci/ats.c:332
Inline: False
```
**Symbols:**

```
c000000000885f30-c000000000885fd8: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffe0004df5f8)
Location: drivers/pci/ats.c:332
Inline: False
```
**Symbols:**

```
ffffffe0004df5f8-ffffffe0004df660: pci_disable_pasid (STB_GLOBAL)
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
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8159fbc0)
Location: drivers/pci/ats.c:332
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8159fbc0-ffffffff8159fc01: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158ed50)
Location: drivers/pci/ats.c:332
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8158ed50-ffffffff8158ed91: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a0140)
Location: drivers/pci/ats.c:332
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815a0140-ffffffff815a0181: pci_disable_pasid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ba570)
Location: drivers/pci/ats.c:332
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815ba570-ffffffff815ba5b1: pci_disable_pasid (STB_GLOBAL)
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
