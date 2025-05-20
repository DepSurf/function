# Function: <code>pci_device_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8152b7c0)
Location: drivers/iommu/iommu.c:749
Inline: False
```
**Symbols:**

```
ffffffff8152b7c0-ffffffff8152b8fc: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8157ebf0)
Location: drivers/iommu/iommu.c:736
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff8157ebf0-ffffffff8157ed2c: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815ab620)
Location: drivers/iommu/iommu.c:887
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff815ab620-ffffffff815ab75c: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c1290)
Location: drivers/iommu/iommu.c:925
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff815c1290-ffffffff815c13af: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627a30)
Location: drivers/iommu/iommu.c:927
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff81627a30-ffffffff81627b4f: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81662600)
Location: drivers/iommu/iommu.c:928
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff81662600-ffffffff81662723: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680790)
Location: drivers/iommu/iommu.c:994
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff81680790-ffffffff816808b3: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1212
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
```
**Symbols:**

```
ffffffff816b8a2c-ffffffff816b8a46: pci_device_group.cold (STB_LOCAL)
ffffffff816b8000-ffffffff816b8118: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816dad60)
Location: drivers/iommu/iommu.c:1268
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:intel_iommu_device_group
```
**Symbols:**

```
ffffffff816dad60-ffffffff816dae7d: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178deb0)
Location: drivers/iommu/iommu.c:1372
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/intel/iommu.c:intel_iommu_device_group
```
**Symbols:**

```
ffffffff8178deb0-ffffffff8178dfcd: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b9c20)
Location: drivers/iommu/iommu.c:1404
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/intel/iommu.c:intel_iommu_device_group
```
**Symbols:**

```
ffffffff817b9c20-ffffffff817b9d3d: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179cdd0)
Location: drivers/iommu/iommu.c:1433
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/intel/iommu.c:intel_iommu_device_group
```
**Symbols:**

```
ffffffff8179cdd0-ffffffff8179ceed: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81825aa0)
Location: drivers/iommu/iommu.c:1448
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/intel/iommu.c:intel_iommu_device_group
  - drivers/iommu/virtio-iommu.c:viommu_device_group
```
**Symbols:**

```
ffffffff81825aa0-ffffffff81825bbd: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff819657e0)
Location: drivers/iommu/iommu.c:1422
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/intel/iommu.c:intel_iommu_device_group
  - drivers/iommu/virtio-iommu.c:viommu_device_group
```
**Symbols:**

```
ffffffff819657e0-ffffffff81965917: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ace8a0)
Location: drivers/iommu/iommu.c:1543
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/intel/iommu.c:intel_iommu_device_group
  - drivers/iommu/virtio-iommu.c:viommu_device_group
```
**Symbols:**

```
ffffffff81ace8a0-ffffffff81ace9d7: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1d240)
Location: drivers/iommu/iommu.c:1534
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/intel/iommu.c:intel_iommu_device_group
  - drivers/iommu/virtio-iommu.c:viommu_device_group
```
**Symbols:**

```
ffffffff81b1d240-ffffffff81b1d377: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b737c0)
Location: drivers/iommu/iommu.c:1699
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_device_group
  - drivers/iommu/intel/iommu.c:intel_iommu_device_group
  - drivers/iommu/virtio-iommu.c:viommu_device_group
```
**Symbols:**

```
ffffffff81b737c0-ffffffff81b738f7: pci_device_group (STB_GLOBAL)
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
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c6c98)
Location: drivers/iommu/iommu.c:1268
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_group
  - drivers/iommu/virtio-iommu.c:viommu_device_group
```
**Symbols:**

```
ffff8000108c6c98-ffff8000108c6db8: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bdc50)
Location: drivers/iommu/iommu.c:1268
Inline: False
```
**Symbols:**

```
c09bdc50-c09bdda0: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096de90)
Location: drivers/iommu/iommu.c:1268
Inline: False
```
**Symbols:**

```
c00000000096de90-c00000000096e050: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a07b0)
Location: drivers/iommu/iommu.c:1268
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:intel_iommu_device_group
```
**Symbols:**

```
ffffffff816a07b0-ffffffff816a08cd: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167e1a0)
Location: drivers/iommu/iommu.c:1268
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:intel_iommu_device_group
```
**Symbols:**

```
ffffffff8167e1a0-ffffffff8167e2bd: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cea20)
Location: drivers/iommu/iommu.c:1268
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:intel_iommu_device_group
```
**Symbols:**

```
ffffffff816cea20-ffffffff816ceb3d: pci_device_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct iommu_group *pci_device_group(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e8f90)
Location: drivers/iommu/iommu.c:1268
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_device_group
  - drivers/iommu/intel-iommu.c:intel_iommu_device_group
```
**Symbols:**

```
ffffffff816e8f90-ffffffff816e90ad: pci_device_group (STB_GLOBAL)
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
