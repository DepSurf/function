# Function: <code>iommu_dma_sync_single_for_device</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (0)
Location: drivers/iommu/dma-iommu.c:685
Inline: False
```
**Symbols:**

```
ffffffff817920a0-ffffffff817920ab: iommu_dma_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817be4c0)
Location: drivers/iommu/dma-iommu.c:772
Inline: True
```
**Symbols:**

```
ffffffff817be4c0-ffffffff817be534: iommu_dma_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a15e0)
Location: drivers/iommu/dma-iommu.c:791
Inline: True
```
**Symbols:**

```
ffffffff817a15e0-ffffffff817a1653: iommu_dma_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182a0e0)
Location: drivers/iommu/dma-iommu.c:811
Inline: True
```
**Symbols:**

```
ffffffff8182a0e0-ffffffff8182a154: iommu_dma_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196a640)
Location: drivers/iommu/dma-iommu.c:917
Inline: True
```
**Symbols:**

```
ffffffff8196a640-ffffffff8196a6cd: iommu_dma_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad46a0)
Location: drivers/iommu/dma-iommu.c:925
Inline: True
```
**Symbols:**

```
ffffffff81ad46a0-ffffffff81ad472d: iommu_dma_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b22e70)
Location: drivers/iommu/dma-iommu.c:966
Inline: True
```
**Symbols:**

```
ffffffff81b22e70-ffffffff81b22efd: iommu_dma_sync_single_for_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b7a005)
Location: drivers/iommu/dma-iommu.c:1085
Inline: True
```
**Symbols:**

```
ffffffff81b7a1b0-ffffffff81b7a278: iommu_dma_sync_single_for_device (STB_LOCAL)
ffffffff821f6da0-ffffffff821f6db5: iommu_dma_sync_single_for_device.cold (STB_LOCAL)
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
void iommu_dma_sync_single_for_device(struct device *dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c95a8)
Location: drivers/iommu/dma-iommu.c:664
Inline: True
```
**Symbols:**

```
ffff8000108c95a8-ffff8000108c960c: iommu_dma_sync_single_for_device (STB_LOCAL)
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
