# Function: <code>pci_disable_ats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81455dd0)
Location: drivers/pci/ats.c:78
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81455dd0-ffffffff81455e93: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814a29f0)
Location: drivers/pci/ats.c:78
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814a29f0-ffffffff814a2ab3: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814c4640)
Location: drivers/pci/ats.c:78
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814c4640-ffffffff814c4703: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814ce8e0)
Location: drivers/pci/ats.c:78
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff814ce8e0-ffffffff814ce988: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8150eb60)
Location: drivers/pci/ats.c:78
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8150eb60-ffffffff8150ec08: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81543a60)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81543a60-ffffffff81543b0a: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8155ade0)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8155ade0-ffffffff8155ae8a: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158b097)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8158b1ca-ffffffff8158b1dd: pci_disable_ats.cold (STB_LOCAL)
ffffffff8158b060-ffffffff8158b10a: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ac990)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815ac990-ffffffff815aca3a: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816555a0)
Location: drivers/pci/ats.c:94
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816555a0-ffffffff81655623: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81675b40)
Location: drivers/pci/ats.c:94
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81675b40-ffffffff81675bc3: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81658070)
Location: drivers/pci/ats.c:94
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff81658070-ffffffff816580f3: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816ca0a0)
Location: drivers/pci/ats.c:94
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff816ca0a0-ffffffff816ca123: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f03f0)
Location: drivers/pci/ats.c:94
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff817f03f0-ffffffff817f0485: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81918650)
Location: drivers/pci/ats.c:94
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:iommu_disable_pci_caps
```
**Symbols:**

```
ffffffff81918650-ffffffff819186e5: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195bc70)
Location: drivers/pci/ats.c:94
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:iommu_disable_pci_caps
```
**Symbols:**

```
ffffffff8195bc70-ffffffff8195bd05: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5290)
Location: drivers/pci/ats.c:95
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:detach_device
  - drivers/iommu/intel/iommu.c:iommu_disable_pci_caps
```
**Symbols:**

```
ffffffff819a5290-ffffffff819a5325: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffff800010716540)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_detach_dev
```
**Symbols:**

```
ffff800010716540-ffff800010716618: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c08a0f54)
Location: drivers/pci/ats.c:80
Inline: True
```
**Symbols:**

```
c08a0f54-c08a1050: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c000000000886830)
Location: drivers/pci/ats.c:80
Inline: True
```
**Symbols:**

```
c000000000886830-c00000000088693c: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffe0004dfad0)
Location: drivers/pci/ats.c:80
Inline: True
```
**Symbols:**

```
ffffffe0004dfad0-ffffffe0004dfb74: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a0160)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815a0160-ffffffff815a020a: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158f2f0)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff8158f2f0-ffffffff8158f39a: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a06e0)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815a06e0-ffffffff815a078a: pci_disable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_disable_ats(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815bab10)
Location: drivers/pci/ats.c:80
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/amd_iommu.c:detach_device
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
```
**Symbols:**

```
ffffffff815bab10-ffffffff815babba: pci_disable_ats (STB_GLOBAL)
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
