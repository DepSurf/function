# Function: <code>vfio_iommu_group_get</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d0c20)
Location: drivers/vfio/vfio.c:116
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817d0c20-ffffffff817d0ccc: vfio_iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8189b3d0)
Location: drivers/vfio/vfio.c:117
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8189b3d0-ffffffff8189b47c: vfio_iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff818a9fe0)
Location: drivers/vfio/vfio.c:117
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff818a9fe0-ffffffff818aa08c: vfio_iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8188d380)
Location: drivers/vfio/vfio.c:107
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8188d380-ffffffff8188d42c: vfio_iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8192094e)
Location: drivers/vfio/vfio.c:180
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
```
**Symbols:**

```
ffffffff81d11693-ffffffff81d116a7: vfio_iommu_group_get.cold (STB_LOCAL)
ffffffff81920900-ffffffff819209ba: vfio_iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab0610)
Location: drivers/vfio/vfio.c:116
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
c000000000ab0610-c000000000ab0770: vfio_iommu_group_get (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177acd0)
Location: drivers/vfio/vfio.c:116
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff8177acd0-ffffffff8177ad7c: vfio_iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c5aa0)
Location: drivers/vfio/vfio.c:116
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817c5aa0-ffffffff817c5b4c: vfio_iommu_group_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct iommu_group *vfio_iommu_group_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817dfd40)
Location: drivers/vfio/vfio.c:116
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
**Symbols:**

```
ffffffff817dfd40-ffffffff817dfdec: vfio_iommu_group_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
