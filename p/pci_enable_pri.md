# Function: <code>pci_enable_pri</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81455c80)
Location: drivers/pci/ats.c:150
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81455c80-ffffffff81455d73: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814a28a0)
Location: drivers/pci/ats.c:150
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff814a28a0-ffffffff814a2993: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814c44f0)
Location: drivers/pci/ats.c:150
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff814c44f0-ffffffff814c45e3: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814ce700)
Location: drivers/pci/ats.c:150
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff814ce700-ffffffff814ce7de: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8150e980)
Location: drivers/pci/ats.c:150
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
```
**Symbols:**

```
ffffffff8150e980-ffffffff8150ea5e: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81543890)
Location: drivers/pci/ats.c:152
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81543890-ffffffff8154396e: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8155ac10)
Location: drivers/pci/ats.c:152
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8155ac10-ffffffff8155acee: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/ats.c (0)
Location: drivers/pci/ats.c:179
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158b1b2-ffffffff8158b1ca: pci_enable_pri.cold (STB_LOCAL)
ffffffff8158ae80-ffffffff8158af53: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ac7b0)
Location: drivers/pci/ats.c:179
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ac7b0-ffffffff815ac88e: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81655a60)
Location: drivers/pci/ats.c:195
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81655a60-ffffffff81655b5d: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81676000)
Location: drivers/pci/ats.c:196
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81676000-ffffffff816760fd: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81658530)
Location: drivers/pci/ats.c:196
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81658530-ffffffff8165862e: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816ca570)
Location: drivers/pci/ats.c:196
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816ca570-ffffffff816ca66e: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f0970)
Location: drivers/pci/ats.c:196
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff817f0970-ffffffff817f0a74: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81918c90)
Location: drivers/pci/ats.c:196
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_pci_caps
```
**Symbols:**

```
ffffffff81918c90-ffffffff81918d94: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195c2b0)
Location: drivers/pci/ats.c:196
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff8195c2b0-ffffffff8195c3b4: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a58d0)
Location: drivers/pci/ats.c:197
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_pdev_enable_cap_pri
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat
```
**Symbols:**

```
ffffffff819a58d0-ffffffff819a59d4: pci_enable_pri (STB_GLOBAL)
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
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffff800010716300)
Location: drivers/pci/ats.c:179
Inline: False
```
**Symbols:**

```
ffff800010716300-ffff8000107163f4: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c08a0d4c)
Location: drivers/pci/ats.c:179
Inline: False
```
**Symbols:**

```
c08a0d4c-c08a0e58: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c000000000886580)
Location: drivers/pci/ats.c:179
Inline: False
```
**Symbols:**

```
c000000000886580-c000000000886708: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffe0004df928)
Location: drivers/pci/ats.c:179
Inline: False
```
**Symbols:**

```
ffffffe0004df928-ffffffe0004df9fc: pci_enable_pri (STB_GLOBAL)
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
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8159ff80)
Location: drivers/pci/ats.c:179
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8159ff80-ffffffff815a005e: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158f110)
Location: drivers/pci/ats.c:179
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158f110-ffffffff8158f1ee: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a0500)
Location: drivers/pci/ats.c:179
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815a0500-ffffffff815a05de: pci_enable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_enable_pri(struct pci_dev *pdev, u32 reqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ba930)
Location: drivers/pci/ats.c:179
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ba930-ffffffff815baa0e: pci_enable_pri (STB_GLOBAL)
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
