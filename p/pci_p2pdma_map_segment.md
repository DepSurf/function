# Function: <code>pci_p2pdma_map_segment</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum pci_p2pdma_map_type pci_p2pdma_map_segment(struct pci_p2pdma_map_state *state, struct device *dev, struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8191d330)
Location: drivers/pci/p2pdma.c:1017
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff8191d330-ffffffff8191d4ce: pci_p2pdma_map_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum pci_p2pdma_map_type pci_p2pdma_map_segment(struct pci_p2pdma_map_state *state, struct device *dev, struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff819608f0)
Location: drivers/pci/p2pdma.c:1018
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff819608f0-ffffffff81960a92: pci_p2pdma_map_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum pci_p2pdma_map_type pci_p2pdma_map_segment(struct pci_p2pdma_map_state *state, struct device *dev, struct scatterlist *sg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff819aa010)
Location: drivers/pci/p2pdma.c:1016
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff819aa010-ffffffff819aa1ad: pci_p2pdma_map_segment (STB_GLOBAL)
```
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
