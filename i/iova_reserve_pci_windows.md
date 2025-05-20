# Function: <code>iova_reserve_pci_windows</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int iova_reserve_pci_windows(struct pci_dev *dev, struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:195
Inline: False
```
**Symbols:**

```
ffffffff81791ee0-ffffffff81791fdd: iova_reserve_pci_windows (STB_LOCAL)
ffffffff81792cc1-ffffffff81792cdf: iova_reserve_pci_windows.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iova_reserve_pci_windows(struct pci_dev *dev, struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:217
Inline: False
```
**Symbols:**

```
ffffffff817be160-ffffffff817be25d: iova_reserve_pci_windows (STB_LOCAL)
ffffffff81c0d6c8-ffffffff81c0d6e6: iova_reserve_pci_windows.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a1a5b)
Location: drivers/iommu/dma-iommu.c:221
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iova_reserve_pci_windows(struct pci_dev *dev, struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:221
Inline: False
```
**Symbols:**

```
ffffffff8182a410-ffffffff8182a599: iova_reserve_pci_windows (STB_LOCAL)
ffffffff81d01c6d-ffffffff81d01d2d: iova_reserve_pci_windows.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iova_reserve_pci_windows(struct pci_dev *dev, struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:427
Inline: False
```
**Symbols:**

```
ffffffff8196a7f0-ffffffff8196a9b0: iova_reserve_pci_windows (STB_LOCAL)
ffffffff81eca11b-ffffffff81eca1eb: iova_reserve_pci_windows.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iova_reserve_pci_windows(struct pci_dev *dev, struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:431
Inline: False
```
**Symbols:**

```
ffffffff81ad4e40-ffffffff81ad5026: iova_reserve_pci_windows (STB_LOCAL)
ffffffff82097e16-ffffffff82097ebd: iova_reserve_pci_windows.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iova_reserve_pci_windows(struct pci_dev *dev, struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:434
Inline: False
```
**Symbols:**

```
ffffffff81b235f0-ffffffff81b237d6: iova_reserve_pci_windows (STB_LOCAL)
ffffffff82118e26-ffffffff82118ecd: iova_reserve_pci_windows.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iova_reserve_pci_windows(struct pci_dev *dev, struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:515
Inline: False
```
**Symbols:**

```
ffffffff81b7a370-ffffffff81b7a556: iova_reserve_pci_windows (STB_LOCAL)
ffffffff821f6dca-ffffffff821f6e71: iova_reserve_pci_windows.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108ca8a0)
Location: drivers/iommu/dma-iommu.c:194
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_setup_dma_ops
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
