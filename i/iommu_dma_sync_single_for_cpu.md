# Function: <code>iommu_dma_sync_single_for_cpu</code>

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
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81791840)
Location: drivers/iommu/dma-iommu.c:673
Inline: True
```
**Symbols:**

```
ffffffff81791840-ffffffff8179184b: iommu_dma_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817be540)
Location: drivers/iommu/dma-iommu.c:756
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffffffff817be540-ffffffff817be5b1: iommu_dma_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a1660)
Location: drivers/iommu/dma-iommu.c:775
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffffffff817a1660-ffffffff817a16d3: iommu_dma_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182a160)
Location: drivers/iommu/dma-iommu.c:795
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffffffff8182a160-ffffffff8182a1d4: iommu_dma_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196a6d0)
Location: drivers/iommu/dma-iommu.c:901
Inline: True
```
**Symbols:**

```
ffffffff8196a6d0-ffffffff8196a75d: iommu_dma_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad4740)
Location: drivers/iommu/dma-iommu.c:909
Inline: True
```
**Symbols:**

```
ffffffff81ad4740-ffffffff81ad47cd: iommu_dma_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b22f10)
Location: drivers/iommu/dma-iommu.c:950
Inline: True
```
**Symbols:**

```
ffffffff81b22f10-ffffffff81b22f9d: iommu_dma_sync_single_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7a105)
Location: drivers/iommu/dma-iommu.c:1069
Inline: True
```
**Symbols:**

```
ffffffff81b7a290-ffffffff81b7a358: iommu_dma_sync_single_for_cpu (STB_LOCAL)
ffffffff821f6db5-ffffffff821f6dca: iommu_dma_sync_single_for_cpu.cold (STB_LOCAL)
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
void iommu_dma_sync_single_for_cpu(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c9644)
Location: drivers/iommu/dma-iommu.c:652
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
  - drivers/iommu/dma-iommu.c:iommu_dma_unmap_page
```
**Symbols:**

```
ffff8000108c9df0-ffff8000108c9e54: iommu_dma_sync_single_for_cpu (STB_LOCAL)
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
