# Function: <code>pci_prg_resp_pasid_required</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158ada0)
Location: drivers/pci/ats.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158ada0-ffffffff8158ae01: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ac6d0)
Location: drivers/pci/ats.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ac6d0-ffffffff815ac731: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81655c10)
Location: drivers/pci/ats.c:321
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81655c10-ffffffff81655c35: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816761b0)
Location: drivers/pci/ats.c:322
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816761b0-ffffffff816761d5: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816586e0)
Location: drivers/pci/ats.c:322
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816586e0-ffffffff81658705: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816ca720)
Location: drivers/pci/ats.c:322
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816ca720-ffffffff816ca745: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f0b60)
Location: drivers/pci/ats.c:322
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff817f0b60-ffffffff817f0b8b: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81918eb0)
Location: drivers/pci/ats.c:322
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_pci_caps
```
**Symbols:**

```
ffffffff81918eb0-ffffffff81918edb: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195c4d0)
Location: drivers/pci/ats.c:322
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff8195c4d0-ffffffff8195c4fb: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5af0)
Location: drivers/pci/ats.c:323
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_pdev_enable_cap_pri
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff819a5af0-ffffffff819a5b1b: pci_prg_resp_pasid_required (STB_GLOBAL)
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
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffff800010716208)
Location: drivers/pci/ats.c:410
Inline: False
```
**Symbols:**

```
ffff800010716208-ffff80001071627c: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c08a0c44)
Location: drivers/pci/ats.c:410
Inline: False
```
**Symbols:**

```
c08a0c44-c08a0cc0: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c000000000886430)
Location: drivers/pci/ats.c:410
Inline: False
```
**Symbols:**

```
c000000000886430-c0000000008864c4: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffe0004df892)
Location: drivers/pci/ats.c:410
Inline: False
```
**Symbols:**

```
ffffffe0004df892-ffffffe0004df8da: pci_prg_resp_pasid_required (STB_GLOBAL)
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
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8159fea0)
Location: drivers/pci/ats.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8159fea0-ffffffff8159ff01: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158f030)
Location: drivers/pci/ats.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158f030-ffffffff8158f091: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a0420)
Location: drivers/pci/ats.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815a0420-ffffffff815a0481: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ba850)
Location: drivers/pci/ats.c:410
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ba850-ffffffff815ba8b1: pci_prg_resp_pasid_required (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
