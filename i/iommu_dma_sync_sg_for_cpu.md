# Function: <code>iommu_dma_sync_sg_for_cpu</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81791850)
Location: drivers/iommu/dma-iommu.c:697
Inline: True
```
**Symbols:**

```
ffffffff81791850-ffffffff8179185b: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817be310)
Location: drivers/iommu/dma-iommu.c:788
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffffffff817be310-ffffffff817be3a7: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a1430)
Location: drivers/iommu/dma-iommu.c:807
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffffffff817a1430-ffffffff817a14c9: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182a770)
Location: drivers/iommu/dma-iommu.c:827
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffffffff8182a770-ffffffff8182a832: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196ac70)
Location: drivers/iommu/dma-iommu.c:933
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffffffff8196ac70-ffffffff8196ad41: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad4c60)
Location: drivers/iommu/dma-iommu.c:941
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffffffff81ad4c60-ffffffff81ad4d31: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b23510)
Location: drivers/iommu/dma-iommu.c:982
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffffffff81b23510-ffffffff81b235d4: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:1101
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffffffff81b7a0b0-ffffffff81b7a19b: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
ffffffff821f6d7d-ffffffff821f6da0: iommu_dma_sync_sg_for_cpu.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_dma_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c9514)
Location: drivers/iommu/dma-iommu.c:676
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg
```
**Symbols:**

```
ffff8000108c93f0-ffff8000108c9488: iommu_dma_sync_sg_for_cpu.part.0 (STB_LOCAL)
ffff8000108c9488-ffff8000108c94dc: iommu_dma_sync_sg_for_cpu (STB_LOCAL)
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
</ul>
