# Function: <code>pci_disable_pri</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81455990)
Location: drivers/pci/ats.c:183
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81455990-ffffffff81455a16: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814a25c0)
Location: drivers/pci/ats.c:183
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814a25c0-ffffffff814a2646: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814c4210)
Location: drivers/pci/ats.c:183
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814c4210-ffffffff814c4296: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814ce4d0)
Location: drivers/pci/ats.c:187
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814ce4d0-ffffffff814ce55f: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8150e750)
Location: drivers/pci/ats.c:187
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8150e750-ffffffff8150e7df: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81543660)
Location: drivers/pci/ats.c:189
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81543660-ffffffff815436ef: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8155a9e0)
Location: drivers/pci/ats.c:189
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8155a9e0-ffffffff8155aa6f: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/ats.c (0)
Location: drivers/pci/ats.c:216
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8158b187-ffffffff8158b19a: pci_disable_pri.cold (STB_LOCAL)
ffffffff8158abe0-ffffffff8158ac6f: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ac510)
Location: drivers/pci/ats.c:216
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815ac510-ffffffff815ac59f: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81655630)
Location: drivers/pci/ats.c:241
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81655630-ffffffff816556bf: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81675bd0)
Location: drivers/pci/ats.c:242
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81675bd0-ffffffff81675c5f: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81658100)
Location: drivers/pci/ats.c:242
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81658100-ffffffff8165818f: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816ca130)
Location: drivers/pci/ats.c:242
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816ca130-ffffffff816ca1bf: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f0490)
Location: drivers/pci/ats.c:242
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff817f0490-ffffffff817f0531: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81918700)
Location: drivers/pci/ats.c:242
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_disable_pci_caps
```
**Symbols:**

```
ffffffff81918700-ffffffff819187a1: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195bd20)
Location: drivers/pci/ats.c:242
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
```
**Symbols:**

```
ffffffff8195bd20-ffffffff8195bdc1: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5340)
Location: drivers/pci/ats.c:243
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:intel_iommu_dev_disable_feat
```
**Symbols:**

```
ffffffff819a5340-ffffffff819a53e1: pci_disable_pri (STB_GLOBAL)
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
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffff800010715ff8)
Location: drivers/pci/ats.c:216
Inline: False
```
**Symbols:**

```
ffff800010715ff8-ffff8000107160a8: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c08a0a00)
Location: drivers/pci/ats.c:216
Inline: False
```
**Symbols:**

```
c08a0a00-c08a0ac8: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c000000000886140)
Location: drivers/pci/ats.c:216
Inline: False
```
**Symbols:**

```
c000000000886140-c000000000886238: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffe0004df70c)
Location: drivers/pci/ats.c:216
Inline: False
```
**Symbols:**

```
ffffffe0004df70c-ffffffe0004df79a: pci_disable_pri (STB_GLOBAL)
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
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8159fce0)
Location: drivers/pci/ats.c:216
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8159fce0-ffffffff8159fd6f: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158ee70)
Location: drivers/pci/ats.c:216
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8158ee70-ffffffff8158eeff: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a0260)
Location: drivers/pci/ats.c:216
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815a0260-ffffffff815a02ef: pci_disable_pri (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_disable_pri(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ba690)
Location: drivers/pci/ats.c:216
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815ba690-ffffffff815ba71f: pci_disable_pri (STB_GLOBAL)
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
