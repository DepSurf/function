# Function: <code>iommu_dma_sync_sg_for_device</code>

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
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:711
Inline: True
```
**Symbols:**

```
ffffffff81792090-ffffffff8179209b: iommu_dma_sync_sg_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817be270)
Location: drivers/iommu/dma-iommu.c:808
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff817be270-ffffffff817be30a: iommu_dma_sync_sg_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a1390)
Location: drivers/iommu/dma-iommu.c:827
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff817a1390-ffffffff817a1429: iommu_dma_sync_sg_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182a340)
Location: drivers/iommu/dma-iommu.c:843
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff8182a340-ffffffff8182a402: iommu_dma_sync_sg_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196ab90)
Location: drivers/iommu/dma-iommu.c:949
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff8196ab90-ffffffff8196ac61: iommu_dma_sync_sg_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad4d50)
Location: drivers/iommu/dma-iommu.c:957
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff81ad4d50-ffffffff81ad4e21: iommu_dma_sync_sg_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b23430)
Location: drivers/iommu/dma-iommu.c:998
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff81b23430-ffffffff81b234f4: iommu_dma_sync_sg_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:1117
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffffffff81b79fb0-ffffffff81b7a09b: iommu_dma_sync_sg_for_device (STB_LOCAL)
ffffffff821f6d5a-ffffffff821f6d7d: iommu_dma_sync_sg_for_device.cold (STB_LOCAL)
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
void iommu_dma_sync_sg_for_device(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c9b00)
Location: drivers/iommu/dma-iommu.c:690
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_map_sg
```
**Symbols:**

```
ffff8000108c9300-ffff8000108c9398: iommu_dma_sync_sg_for_device.part.0 (STB_LOCAL)
ffff8000108c9398-ffff8000108c93ec: iommu_dma_sync_sg_for_device (STB_LOCAL)
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
