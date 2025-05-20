# Function: <code>pci_enable_ats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81455830)
Location: drivers/pci/ats.c:38
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81455830-ffffffff814558e0: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814a2460)
Location: drivers/pci/ats.c:38
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff814a2460-ffffffff814a2510: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814c40b0)
Location: drivers/pci/ats.c:38
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff814c40b0-ffffffff814c4160: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff814ce340)
Location: drivers/pci/ats.c:38
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff814ce340-ffffffff814ce3cc: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8150e5b0)
Location: drivers/pci/ats.c:38
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
```
**Symbols:**

```
ffffffff8150e5b0-ffffffff8150e644: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815434b0)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815434b0-ffffffff81543544: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8155a830)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8155a830-ffffffff8155a8c4: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/ats.c (0)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158b144-ffffffff8158b15c: pci_enable_ats.cold (STB_LOCAL)
ffffffff8158a9d0-ffffffff8158aa69: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ac300)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ac300-ffffffff815ac39b: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816554b0)
Location: drivers/pci/ats.c:56
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816554b0-ffffffff81655547: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81675a50)
Location: drivers/pci/ats.c:56
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:pdev_iommuv2_enable
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81675a50-ffffffff81675ae7: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81657f80)
Location: drivers/pci/ats.c:56
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff81657f80-ffffffff81658017: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff816c9fb0)
Location: drivers/pci/ats.c:56
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff816c9fb0-ffffffff816ca047: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff817f02c0)
Location: drivers/pci/ats.c:56
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff817f02c0-ffffffff817f036a: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff81918500)
Location: drivers/pci/ats.c:56
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:iommu_enable_pci_caps
```
**Symbols:**

```
ffffffff81918500-ffffffff819185aa: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8195bb20)
Location: drivers/pci/ats.c:56
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff8195bb20-ffffffff8195bbca: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff819a5140)
Location: drivers/pci/ats.c:57
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/intel/iommu.c:dmar_domain_attach_device
```
**Symbols:**

```
ffffffff819a5140-ffffffff819a51ea: pci_enable_ats (STB_GLOBAL)
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
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffff800010716618)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev
```
**Symbols:**

```
ffff800010716618-ffff8000107166e8: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c08a0730)
Location: drivers/pci/ats.c:40
Inline: False
```
**Symbols:**

```
c08a0730-c08a0810: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (c000000000885cf0)
Location: drivers/pci/ats.c:40
Inline: False
```
**Symbols:**

```
c000000000885cf0-c000000000885e00: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffe0004df49e)
Location: drivers/pci/ats.c:40
Inline: False
```
**Symbols:**

```
ffffffe0004df49e-ffffffe0004df542: pci_enable_ats (STB_GLOBAL)
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
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8159fad0)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8159fad0-ffffffff8159fb6b: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff8158ec60)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff8158ec60-ffffffff8158ecfb: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815a0050)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815a0050-ffffffff815a00eb: pci_enable_ats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_enable_ats(struct pci_dev *dev, int ps);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/ats.c (ffffffff815ba480)
Location: drivers/pci/ats.c:40
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/amd_iommu.c:attach_device
  - drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb
```
**Symbols:**

```
ffffffff815ba480-ffffffff815ba51b: pci_enable_ats (STB_GLOBAL)
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
